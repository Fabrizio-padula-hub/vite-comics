<script>
import AppHeader from "./components/AppHeader.vue";
import AppProductsList from "./components/AppProductsList.vue";
import AppInfoList from "./components/AppInfoList.vue";
import AppInfoFooter from "./components/AppInfoFooter.vue";
import AppFollowFooter from "./components/AppFollowFooter.vue";
import AppHero from "./components/AppHero.vue";

export default{
  components: {
    AppHeader,
    AppProductsList,
    AppInfoList,
    AppInfoFooter,
    AppFollowFooter,
    AppHero,
  }
}

</script>

<template>

  <header>
    <AppHeader></AppHeader>
  </header>

  <main>
    <AppHero></AppHero>
    <AppProductsList></AppProductsList>
    <AppInfoList></AppInfoList>
  </main>

  <footer>
    <AppInfoFooter></AppInfoFooter>
    <AppFollowFooter></AppFollowFooter>

  </footer>
  
</template>

<style lang="scss">
 @use './style/generic';

</style>
