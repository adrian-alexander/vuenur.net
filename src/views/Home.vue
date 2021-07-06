<template>
  <div
    id="top"
    class="w-full text-lunur-100 from-black via-black to-lunur-700 bg-gradient-to-b relative">
    <nav id="navbar" class="sticky top-0 z-10 bg-black">
      <div class="max-w-7xl mx-auto px-2 sm:px-6 lg:px-8">
        <div class="relative flex items-center justify-between h-16">
          <HamburgerButton />
          <LogoAndText />
          <Links />
          <Works />
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
import HamburgerButton from "../components/HamburgerButton.vue";
import LogoAndText from "../components/LogoAndText.vue";
import Links from "../components/Links.vue";
import Works from "../components/Works.vue";

export default {
  name: "Home",
  components: { HamburgerButton, LogoAndText, Links, Works },
};
</script>
