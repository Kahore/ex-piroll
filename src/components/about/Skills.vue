<template>
  <section>
    <div class="row mt-4">
      <h3 class="col-md-12">Professional Skills</h3>
    </div>
    <div
      v-for="skill in skills"
      :key="skill.id">
      <skills-item
        :skill="skill.skill"
        :skillName="skill.skillName"
      />
    </div>
  </section>

</template>

<script>
export default {
  name: 'AboutSkills',
  components: {
    'skills-item': () => import('@/components/about/SkillsItem.vue')
  },
  data () {
    return {
      skills: [
        {
          id: 1,
          skill: 95,
          skillName: 'Some first skill'
        },
        {
          id: 2,
          skill: 69,
          skillName: 'Some second skill'
        },
        {
          id: 3,
          skill: 78,
          skillName: 'Some third skill'
        }
      ]
    }
  }
}
</script>
