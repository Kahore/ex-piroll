<template>
  <div>
    <section class="row">
      <div class="col-md-4 mt-3">
        <contact-info/>
      </div>
      <div class="offset-md-1 col-md-7 mt-3">
        <contact-form/>
      </div>
    </section>
    <section class="row">
      <div class="col-md-12 mt-3 mb-5">
        <contact-map/>
      </div>
    </section>
  </div>

</template>

<script>
export default {
  name: 'AppContact',
  components: {
    'contact-info': () => import('@/components/contact/Info.vue'),
    'contact-form': () => import('@/components/contact/Form.vue'),
    'contact-map': () => import('@/components/contact/Map.vue')
  }
}
</script>
