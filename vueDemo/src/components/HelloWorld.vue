<template>
  <h1>{{ msg }} + Nathan Soucier </h1>
  <button @click="count++">Starting at: {{ count }}</button>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot tamales.</p>
</template>

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
