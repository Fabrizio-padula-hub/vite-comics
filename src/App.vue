<script>
import AppHeader from "./components/AppHeader.vue";
import AppProductsList from "./components/AppProductsList.vue";
import AppInfoList from "./components/AppInfoList.vue";
import AppInfoFooter from "./components/AppInfoFooter.vue";


export default{
  components: {
    AppHeader,
    AppProductsList,
    AppInfoList,
    AppInfoFooter,
  }
}

</script>

<template>

  <header>
    <AppHeader></AppHeader>
  </header>

  <main>
    <AppProductsList></AppProductsList>
    <AppInfoList></AppInfoList>
  </main>

  <footer>
    <AppInfoFooter></AppInfoFooter>

  </footer>
  
</template>

<style lang="scss">
 @use './style/generic';

</style>
