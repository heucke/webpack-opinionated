<template lang="jade">
section
  hello(:msg='msg')
  br
  input(type='text', v-model='msg')
</template>

<script>
import Hello from './components/Hello.vue'

export default {
  components: {
    Hello
  },
  data () {
    return {
      // note: changing this line won't causes changes
      // with hot-reload because the reloaded component
      // preserves its current state and we are modifying
      // its initial state.
      msg: 'Hello Vue!'
    }
  }
}
</script>

<style lang="sass">
$font: Helvetica, sans-serif;

body {
  font-family: $font;
}
</style>
