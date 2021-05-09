<template>
  <div>
    <p>
      USER ID: {{userId}}
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userId: this.$route.params.id
    }
  },
  name: "_id"
}
</script>

<style scoped>

</style>
