<template>
  <div>
    <Head/>
    <How/>
    <Choice/>
  </div>
</template>

<script>
import Head from '../components/Header.vue'
import How from '../components/How.vue'
import Choice from '../components/Choice.vue'
export default {
  name: 'Home',
  components: {
    Head,
    How,
    Choice
  }
}
</script>
<style>

</style>
