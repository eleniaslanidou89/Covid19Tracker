<template>
  <Logo />
  <Header />
  <div class="container"><router-view /></div>
</template>

<script>
import Header from "@/components/Header";
import Logo from "@/components/Logo";

export default {
  components: {
    Header,
    Logo,
  },
};
</script>
