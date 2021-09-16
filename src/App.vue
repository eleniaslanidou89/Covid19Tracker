<template>
  <Logo />
  <Header />
  <div class="container"><router-view /></div>
</template>

<script>
import Header from "@/components/Header";
import Logo from "@/components/Logo";
import DataTitle from "@/components/DataTitle"

export default {
  components: {
    Header,
    Logo,
    DataTitle,
  },
};
</script>
