<template>
  <div class="bg-[#181A1B] min-h-screen pt-16 px-4 md:px-8">
    <div class="max-w-3xl mx-auto">
      <h1
        class="text-3xl sm:text-4xl font-bold text-[#00FF41] mb-8 drop-shadow-[0_0_6px_#00FF41]"
      >
        Hakkımda
      </h1>
      <div class="space-y-6">
        <div
          class="bg-[#232728] rounded-xl shadow p-6 border border-[#00FF41]/30"
        >
          <h2 class="text-xl font-semibold text-[#00FF41] mb-2">Eğitim</h2>
          <ul class="list-disc list-inside text-gray-200">
            <li>
              Üniversite: Malatya İnönü Üniversitesi Bilgisayar Programcılığı
            </li>
            <li>Lise: Hacı Hüseyin Kölük Mesleki ve Teknik Anadolu Lisesi</li>
          </ul>
        </div>
        <div
          class="bg-[#232728] rounded-xl shadow p-6 border border-[#00FF41]/30"
        >
          <h2 class="text-xl font-semibold text-[#00FF41] mb-2">Yetenekler</h2>
          <div class="grid grid-cols-2 gap-2 text-gray-200">
            <span>Vue.js</span>
            <span>Tailwind CSS</span>
            <span>JavaScript</span>
            <span>Responsive Tasarım</span>
            <span>Django</span>
            <span>Python</span>
            <span>HTML</span>
            <span>CSS</span>
            <span>Docker</span>
          </div>
        </div>
        <div
          class="bg-[#232728] rounded-xl shadow p-6 border border-[#00FF41]/30"
        >
          <h2 class="text-xl font-semibold text-[#00FF41] mb-2">İletişim</h2>
          <div class="flex gap-4 text-gray-200 text-2xl">
            <a
              href="https://github.com/Farukakdmir"
              target="_blank"
              rel="noopener"
              class="hover:text-[#00FF41] transition-colors"
            >
              <i class="mdi mdi-github"></i>
            </a>
            <a
              href="https://www.linkedin.com/in/faruk-akdemir-2b3198308/"
              target="_blank"
              rel="noopener"
              class="hover:text-[#00FF41] transition-colors"
            >
              <i class="mdi mdi-linkedin"></i>
            </a>
            <a href="#" class="hover:text-[#00FF41] transition-colors">
              <i class="mdi mdi-email"></i>
            </a>
          </div>
        </div>
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
