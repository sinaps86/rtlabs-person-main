<template>
    <div class="person__page">
        <div class="person__main-container">
            <PersonHeader class=""/>
            <section class="person__content">
                <p>Content section</p>
            </section>
            <PersonFooter class="row"/>
        </div>
    </div>
</template>

<script>
  import PersonHeader from '../components/person-header'
  import PersonFooter from '../components/person-footer'
  export default {
    name: "person-main",
    components: {
      PersonHeader,
      PersonFooter
    }
  }
</script>

<style scoped>

</style>