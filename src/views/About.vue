<template>
  <div>
    <about-main/>
    <about-statictic/>
    <about-extinfo/>
    <about-skills/>
    <about-need-project/>
  </div>
</template>

<script>
export default {
  name: 'about',
  components: {
    'about-main': () => import('@/components/about/Main.vue'),
    'about-statictic': () => import('@/components/about/Stat.vue'),
    'about-extinfo': () => import('@/components/about/ExtInfo.vue'),
    'about-skills': () => import('@/components/about/Skills.vue'),
    'about-need-project': () => import('@/components/about/NeedAProject.vue')
  }
}
</script>
