<template>
  <div class="row">
    <div class="col-md-6 about-img ">
      <img
        src="@/assets/img/about_image.png"
        alt="about_image">
    </div>
    <div class="col-md-6">
      <h3 class="mt-3">About us</h3>
      <p>At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut perferendis doloribus asperiores repellat.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutExtInfo'
}
</script>

<style lang="scss" scoped>
  .about{
    &-img {
      margin-left: -15px;
    }
  }
@media (max-width: 1200px) {
  .about{
    &-img {
      display: none;
    }
  }
}
</style>
