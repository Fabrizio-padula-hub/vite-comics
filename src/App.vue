<script>
import AppHeader from "./components/AppHeader.vue";
import AppProductsList from "./components/AppProductsList.vue";
import AppInfoList from "./components/AppInfoList.vue";

export default{
  components: {
    AppHeader,
    AppProductsList,
    AppInfoList
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
  
</template>

<style lang="scss">
 @use './style/generic';

</style>
