<template>
  <div id="app">
    <div id="cover"></div>
    <header-com/>
    <todo-com/>
    <footer-com/>
  </div>
</template>

<script>
import HeaderCom from './todo/header.vue'
import FooterCom from './todo/footer.jsx'
import TodoCom from './todo/todo.vue'
export default {
  components: {
    HeaderCom,
    FooterCom,
    TodoCom
  },
  data () {
    return {
      text: 'abfhissg'
    }
  }
}
</script>

<style lang="scss" scoped>
  #app {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    #cover {
      position: absolute;
      left: 0;
      right: 0;
      top: 0;
      bottom: 0;
      background-color: #555;
      opacity: 0.5;
      z-index: -1;
    }
  }
</style>