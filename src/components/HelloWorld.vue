<template>
  <div>
    <h1>{{ msg }}</h1>
    <button @click="count++">count is: {{ count }}</button>
  </div>
</template>

<style scoped>
button {
  background-color: #fff;
  border: 1px solid rgb(0, 0, 0);
  border-radius: 0.5rem;
  padding: 4px;
  margin: 4px;
  color: #000;
  font-size: 1.5rem;
}
</style>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  }
}
</script>
