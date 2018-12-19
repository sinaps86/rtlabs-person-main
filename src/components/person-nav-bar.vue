<template>
    <div class="person__nav-bar">
        <div class="">
            <div class="person__logo-container">
                <div class="person__logo-title">Ключ</div>
                <div class="person__logo-sub-title">Ростелеком</div>
            </div>
            <div class="">
                <PersonMainNav/>
            </div>
            <div class="">
                <PersonProfileControl/>
            </div>
        </div>
    </div>
</template>

<script>
  import PersonMainNav from '../components/peson-main-nav'
  import PersonProfileControl from '../components/person-profile-control'

  export default {
    name: "person-nav-bar",
    components: {
      PersonMainNav,
      PersonProfileControl
    }
  }
</script>

<style scoped>

</style>