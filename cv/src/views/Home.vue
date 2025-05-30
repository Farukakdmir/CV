<template>
  <div
    class="bg-gray-50 min-h-screen pt-16 px-4 md:px-8 flex items-center justify-center relative overflow-hidden"
  >
    <canvas
      id="matrix-canvas"
      class="absolute inset-0 w-full h-full z-0"
    ></canvas>
    <div
      class="flex flex-col items-center justify-center space-y-8 w-full max-w-3xl relative z-10"
    >
      <h1
        class="font-bold text-4xl sm:text-5xl md:text-6xl lg:text-7xl break-words animate-fade-in text-[#00FF41] drop-shadow-[0_0_10px_#00FF41]"
      >
        Hoş Geldiniz
      </h1>
      <p
        class="text-lg sm:text-xl md:text-2xl text-[#00FF41] drop-shadow-[0_0_6px_#00FF41] animate-slide-up break-words"
      >
        Bilgisayar programcısıyım frontend ve backend alanlarında çalışıyorum.
      </p>
    </div>
  </div>
</template>

<script setup>
import { onMounted, onBeforeUnmount } from "vue";

let animationId;

onMounted(() => {
  const canvas = document.getElementById("matrix-canvas");
  const ctx = canvas.getContext("2d");

  // Tam ekran ayarla
  function resizeCanvas() {
    canvas.width = window.innerWidth;
    canvas.height = window.innerHeight;
  }
  resizeCanvas();
  window.addEventListener("resize", resizeCanvas);

  // Matrix karakterleri
  const letters = "01";
  const fontSize = 18;
  const columns = Math.floor(canvas.width / fontSize);
  const drops = Array(columns).fill(1);

  function draw() {
    ctx.fillStyle = "rgba(0, 0, 0, 0.08)";
    ctx.fillRect(0, 0, canvas.width, canvas.height);
    ctx.font = fontSize + "px monospace";
    ctx.fillStyle = "#00FF41";
    for (let i = 0; i < drops.length; i++) {
      const text = letters.charAt(Math.floor(Math.random() * letters.length));
      ctx.fillText(text, i * fontSize, drops[i] * fontSize);
      if (drops[i] * fontSize > canvas.height && Math.random() > 0.975) {
        drops[i] = 0;
      }
      if (Math.random() > 0.7) {
        drops[i]++;
      }
    }
    animationId = requestAnimationFrame(draw);
  }
  draw();

  // Temizlik
  onBeforeUnmount(() => {
    window.removeEventListener("resize", resizeCanvas);
    cancelAnimationFrame(animationId);
  });
});
</script>

<style scoped>
.animate-fade-in {
  animation: fadeIn 1s ease-out;
}

.animate-slide-up {
  animation: slideUp 1s ease-out;
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@keyframes slideUp {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

#matrix-canvas {
  pointer-events: none;
  background: #000;
  opacity: 0.8;
}
</style>
