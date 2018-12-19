<template>
    <div class="person__header">
        <PersonNavBar></PersonNavBar>
        <div class="person__header-content"></div>
    </div>
</template>

<script>
  import PersonNavBar from '../components/person-nav-bar'
  export default {
    name: "person-header",
    components: {
      PersonNavBar
    }
  }
</script>

<style scoped>

</style>