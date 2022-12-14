<template>
  <div>
    <p>I'm on team {{ $route.params.teamSlug }} and my user id is {{ $route.params.userId }}</p>
  </div>
</template>

<script>
export default {
  name: "[id]"
}
</script>

<style scoped>

</style>