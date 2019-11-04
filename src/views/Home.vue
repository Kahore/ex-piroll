<template>
  <div class="home">
    <home-main/>
    <home-work/>
  </div>
</template>

<script>
export default {
  name: 'home',
  components: {
    'home-main': () => import('@/components/home/Main.vue'),
    'home-work': () => import('@/components/home/WorkList.vue')
  }
}
</script>
