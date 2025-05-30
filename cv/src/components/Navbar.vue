<template>
  <nav
    class="fixed top-0 left-0 w-full z-50 bg-[#232728] bg-opacity-95 shadow-lg border-b border-[#00FF41]/40"
  >
    <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between">
      <br />

      <ul class="flex space-x-8">
        <li>
          <router-link
            to="/"
            class="text-[#00FF41] hover:text-white hover:bg-[#00FF41]/20 px-3 py-1 rounded transition-colors duration-200 font-semibold"
            >Anasayfa</router-link
          >
        </li>
        <li>
          <router-link
            to="/about"
            class="text-[#00FF41] hover:text-white hover:bg-[#00FF41]/20 px-3 py-1 rounded transition-colors duration-200 font-semibold"
            >Hakkımda</router-link
          >
        </li>
        <li>
          <router-link
            to="/projects"
            class="text-[#00FF41] hover:text-white hover:bg-[#00FF41]/20 px-3 py-1 rounded transition-colors duration-200 font-semibold"
            >Projeler</router-link
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      menuItems: [
        { name: "Anasayfa", path: "/" },
        { name: "Hakkımda", path: "/about" },
        { name: "Projeler", path: "/projects" },
      ],
    };
  },
};
</script>
