<template>
  <b-container class="mt-1">
    <main-navs></main-navs>
    <div>&nbsp; </div>
    <main-header></main-header>
    <nuxt />
    <main-footer></main-footer>
  </b-container>
</template>

<script>
import MainHeader from "~/components/site/MainHeader";
import MainFooter from "~/components/site/MainFooter";
import MainNavs from "~/components/site/MainNavs";
import MainContent from "~/components/site/MainContent";

export default {
  components: {
    MainHeader,
    MainFooter,
    MainNavs,
  },
};
</script>

<style></style>
