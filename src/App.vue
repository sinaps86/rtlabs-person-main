<template>
  <div id="app">
    <PersonMain></PersonMain>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PersonMain from './components/person-main.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    PersonMain
  }
}
</script>

<style>
  .person__page {
    background-color: lightblue;
  }
  .person__header {
    background-color: #ffbd00;
  }
  .person__nav-bar {
    margin: 0 160px;
  }
  .person__header-content {
    margin: 0 0 0 160px;
  }
  .person__content {

  }
  .person__footer {

  }
</style>
