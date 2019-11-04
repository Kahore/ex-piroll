<template>
  <div id="app" >
    <div class="container">
      <app-navbar/>
      <router-view class="content"/>
    </div>
    <app-footer/>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    'app-navbar': () => import('@/components/layout/Header.vue'),
    'app-footer': () => import('@/components/layout/Footer.vue')
  }
}
</script>

<style lang="scss">

</style>
