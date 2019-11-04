<template>
  <div class="mb-2">
    <span class="col-lg-12">{{skillName}} {{skill}}%</span>
      <div class="progressbar col-lg-3">
        <div class="progressbar-item" :style="{ width: skill + '%' }"></div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'SkillsItem',
  props: {
    skill: {
      type: Number,
      required: true,
      default: 0
    },
    skillName: {
      type: String,
      required: true,
      default: ''
    }
  }
}
</script>

<style lang="scss" scoped>
.progressbar {
  height: 10px;
  width: 300px;
  background-color: #d8d8d8;
  border-radius: 13px;
  padding: 3px;
}

.progressbar-item {
  background-color:#10c9c3;
  height: 4px;
}
</style>
