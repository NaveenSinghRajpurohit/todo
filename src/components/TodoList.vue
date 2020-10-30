<template>
  <div>
      <input type="text" class="todu-input" placeholder="what needs to be done">
<p>todo list goes here</p>
  </div>
</template>

<script>
export default {
  name: 'TodoList',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
.todo-input {
    width: 100%;
    padding: 10px 10px;
    font-size: 18px;
    margin-bottom: 16px;
  
}
</style>
