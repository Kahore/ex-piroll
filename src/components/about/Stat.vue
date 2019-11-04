<template>
  <div class="row statistic">
    <div class="col-lg-4 col-md-5">
      <div class="statistic-img">
        <img
          alt="project"
          class="statistic-img--item"
          src="@/assets/icons/project.svg">
      </div>
      <div class="statistic-text">
        <span>548</span> <br>
        <span>projects completed</span>
      </div>
    </div>
    <div class="col-lg-4 col-md-5">
      <div class="statistic-img">
        <img
          alt="project"
          class="statistic-img--item"
          src="@/assets/icons/working.svg">
      </div>
      <div class="statistic-text">
        <span>1465</span> <br>
        <span>WORKING HOURS</span>
      </div>

    </div>
    <div class="col-lg-4 col-md-5">
      <div class="statistic-img">
        <img
          alt="project"
          src="@/assets/icons/star.svg"
          class="statistic-img--item">
      </div>
      <div class="statistic-text">
        <span>612</span> <br>
        <span>POSITIVE FEEDBACKS</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutStats'
}
</script>

<style lang="scss" scoped>
.statistic {
  background: #10c7c1;
  padding: 2rem;
  &-img{
    display: inline-flex;
    &--item {
      transform: scale(0.5, 0.5);
    }
  }
  &-text{
    display: inline-block;
    color: #fff;
    margin-left: 0.8rem;
  }
}
</style>
