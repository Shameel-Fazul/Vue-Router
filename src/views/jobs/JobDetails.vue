<template>
  <h1>Job details</h1>
  <p>The job id is {{ id }}</p> <!-- Route Parameters -->
</template>

<script>
export default {
  props: ['id'], // Set "props: true" in index.js to also take params as props
  // data() {
  //   return {
  //     id: this.$route.params.id
  //   }
  // }
}
</script>

<style>

</style>