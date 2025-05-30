<template>
  <div class="bg-[#181A1B] min-h-screen pt-16 px-4 md:px-8">
    <div class="flex flex-col items-start justify-start w-full max-w-6xl">
      <h1
        class="font-bold text-transparent bg-clip-text bg-gradient-to-r from-[#00FF41] to-[#00FF41] mb-12 animate-fade-in text-2xl sm:text-3xl md:text-4xl lg:text-5xl break-words"
      >
        Projelerim
      </h1>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 w-full">
        <router-link
          to="/projects/sami-efendi-vakfi"
          class="bg-[#232728] border border-[#00FF41] rounded-xl overflow-hidden shadow-sm transform transition-all duration-300 hover:scale-105 animate-slide-up w-full max-w-full cursor-pointer block"
          style="animation-delay: 0.2s"
        >
          <div class="p-4 sm:p-6">
            <h3
              class="text-lg sm:text-xl font-semibold text-[#00FF41] mb-2 break-words drop-shadow-[0_0_6px_#00FF41]"
            >
              Sami Efendi Vakfı Web Sitesi
            </h3>
            <p class="text-gray-200 mb-4 text-sm sm:text-base break-words">
              Sami Efendi Vakfı için hazırlanan, modern ve kullanıcı dostu bir
              web sitesi projesi.
            </p>
            <div class="flex flex-wrap gap-2">
              <span
                class="px-2 py-1 bg-[#181A1B] rounded-full text-xs sm:text-sm text-[#00FF41] border border-[#00FF41]"
                >Vue.js</span
              >
              <span
                class="px-2 py-1 bg-[#181A1B] rounded-full text-xs sm:text-sm text-[#00FF41] border border-[#00FF41]"
                >Tailwind</span
              >
              <span
                class="px-2 py-1 bg-[#181A1B] rounded-full text-xs sm:text-sm text-[#00FF41] border border-[#00FF41]"
                >Kurumsal</span
              >
            </div>
          </div>
        </router-link>
      </div>
    </div>
  </div>
</template>

<script setup>
// Component logic here
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
</style>
