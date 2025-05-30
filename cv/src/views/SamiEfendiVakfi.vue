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
              Vakıf Yönetim Paneli: Personel girişi, dosya yönetimi ve başvuru
              takip sisteminin yer aldığı yönetim paneli.
            </p>
          </div>
          <div class="flex flex-col items-center">
            <img
              src="/proje%20resmi2.jpg"
              alt="Sami Efendi Vakfı 2"
              class="object-cover rounded-xl h-64 w-auto max-w-full shadow-lg mb-2"
            />
            <p class="text-gray-200 text-center text-base mt-2">
              Yardım Başvuru Formu: Maddi yardım, şahsi yardım ve aile bakım
              desteği başvurularının yapılabileceği form sayfası.
            </p>
          </div>
          <div class="flex flex-col items-center">
            <img
              src="/proje%20resmi3.jpg"
              alt="Sami Efendi Vakfı 3"
              class="object-cover rounded-xl h-64 w-auto max-w-full shadow-lg mb-2"
            />
            <p class="text-gray-200 text-center text-base mt-2">
              Başvuru Takip Sistemi: Başvuru durumu sorgulama, doküman yükleme
              ve bildirim sisteminin yer aldığı takip sayfası.
            </p>
          </div>
          <div class="flex flex-col items-center">
            <img
              src="/proje%20resmi4.jpg"
              alt="Sami Efendi Vakfı 4"
              class="object-cover rounded-xl h-64 w-auto max-w-full shadow-lg mb-2"
            />
            <p class="text-gray-200 text-center text-base mt-2">
              Zekat ve Bağış Sistemi: Zekat, sadaka ve diğer bağışların güvenli
              bir şekilde yapılabileceği bağış sayfası.
            </p>
          </div>
        </div>
        <div class="text-gray-200 space-y-4">
          <p>
            <strong class="text-[#00FF41]">Proje Açıklaması:</strong> Sami
            Efendi Vakfı için geliştirilen bu web uygulaması, vakfın tüm
            operasyonlarını dijital ortamda yönetmek ve yardım süreçlerini daha
            etkili bir şekilde yürütmek amacıyla tasarlanmıştır.
          </p>
          <p>
            <strong class="text-[#00FF41]">Temel Özellikler:</strong>
          </p>
          <ul class="list-disc pl-6 space-y-2">
            <li>
              <strong class="text-[#00FF41]">Vakıf Yönetim Sistemi:</strong>
              <ul class="list-disc pl-6 mt-1">
                <li>Vakıf personeli için güvenli giriş sistemi</li>
                <li>Dosya ve kayıt yönetimi</li>
                <li>Yardım başvurularının takibi</li>
                <li>Mali raporlama ve takip sistemi</li>
              </ul>
            </li>
            <li>
              <strong class="text-[#00FF41]">Yardım Başvuru Sistemi:</strong>
              <ul class="list-disc pl-6 mt-1">
                <li>Maddi yardım başvuruları</li>
                <li>Şahsi yardım başvuruları</li>
                <li>Zekat ve sadaka bağışları</li>
                <li>Aile bakım desteği başvuruları</li>
              </ul>
            </li>
            <li>
              <strong class="text-[#00FF41]">Başvuru Takip Sistemi:</strong>
              <ul class="list-disc pl-6 mt-1">
                <li>Başvuru durumu sorgulama</li>
                <li>Otomatik bildirim sistemi</li>
                <li>Doküman yükleme ve takibi</li>
              </ul>
            </li>
          </ul>
          <p>
            <strong class="text-[#00FF41]">Teknolojiler:</strong> Vue.js,
            Tailwind CSS, Node.js, MongoDB, JWT Authentication
          </p>
          <p>
            <strong class="text-[#00FF41]">Güvenlik Özellikleri:</strong>
          </p>
          <ul class="list-disc pl-6 mt-1">
            <li>SSL sertifikası ile güvenli veri transferi</li>
            <li>Rol tabanlı yetkilendirme sistemi</li>
            <li>Veri şifreleme ve güvenli depolama</li>
            <li>Düzenli yedekleme sistemi</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// Gerekli scriptler buraya eklenebilir
</script>

<style scoped></style>
