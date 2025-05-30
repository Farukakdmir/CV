<template>
  <div class="bg-[#181A1B] min-h-screen pt-16 px-4 md:px-8">
    <div class="max-w-3xl mx-auto">
      <router-link
        to="/projects"
        class="inline-block mb-6 px-4 py-2 bg-[#232728] border border-[#00FF41] text-[#00FF41] rounded-lg font-semibold shadow hover:bg-[#00FF41] hover:text-[#181A1B] transition-colors duration-200"
      >
        ← Geri
      </router-link>
      <div class="bg-[#232728] rounded-xl shadow-md p-6">
        <h1
          class="text-2xl sm:text-3xl font-bold text-[#00FF41] mb-6 drop-shadow-[0_0_6px_#00FF41]"
        >
          Sami Efendi Vakfı Web Sitesi
        </h1>
        <div
          class="flex flex-col gap-8 justify-center mb-6 bg-black/60 p-4 rounded-lg"
        >
          <div class="flex flex-col items-center">
            <img
              src="/proje%20resmi.jpg"
              alt="Sami Efendi Vakfı 1"
              class="object-cover rounded-xl h-64 w-auto max-w-full shadow-lg mb-2"
            />
            <p class="text-gray-200 text-center text-base mt-2">
              Ana sayfa ve genel görünüm: Vakfın kurumsal kimliğini yansıtan
              modern ana sayfa tasarımı.
            </p>
          </div>
          <div class="flex flex-col items-center">
            <img
              src="/proje%20resmi2.jpg"
              alt="Sami Efendi Vakfı 2"
              class="object-cover rounded-xl h-64 w-auto max-w-full shadow-lg mb-2"
            />
            <p class="text-gray-200 text-center text-base mt-2">
              Hizmetler bölümü: Vakfın sunduğu hizmetlerin detaylı ve anlaşılır
              şekilde sunumu.
            </p>
          </div>
          <div class="flex flex-col items-center">
            <img
              src="/proje%20resmi3.jpg"
              alt="Sami Efendi Vakfı 3"
              class="object-cover rounded-xl h-64 w-auto max-w-full shadow-lg mb-2"
            />
            <p class="text-gray-200 text-center text-base mt-2">
              Galeri: Etkinliklerden ve vakıf faaliyetlerinden fotoğrafların yer
              aldığı galeri bölümü.
            </p>
          </div>
          <div class="flex flex-col items-center">
            <img
              src="/proje%20resmi4.jpg"
              alt="Sami Efendi Vakfı 4"
              class="object-cover rounded-xl h-64 w-auto max-w-full shadow-lg mb-2"
            />
            <p class="text-gray-200 text-center text-base mt-2">
              İletişim ve ulaşım: Ziyaretçilerin vakıf ile kolayca iletişime
              geçebileceği ve yol tarifi alabileceği iletişim sayfası.
            </p>
          </div>
        </div>
        <div class="text-gray-200 space-y-4">
          <p>
            <strong class="text-[#00FF41]">Proje Açıklaması:</strong> Sami
            Efendi Vakfı için hazırlanan bu web sitesi, vakfın dijital varlığını
            güçlendirmek ve ziyaretçilere modern, kullanıcı dostu bir deneyim
            sunmak amacıyla tasarlanmıştır.
          </p>
          <p>
            <strong class="text-[#00FF41]">Teknolojiler:</strong> Vue.js,
            Tailwind CSS, Kurumsal Web Tasarımı
          </p>
          <p>
            <strong class="text-[#00FF41]">Özellikler:</strong> Çoklu görsel
            desteği, responsive tasarım, kolay yönetilebilir içerik yapısı.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// Gerekli scriptler buraya eklenebilir
</script>

<style scoped></style>
