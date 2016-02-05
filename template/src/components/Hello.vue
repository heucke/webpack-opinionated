<template lang="jade">
h1 {{ msg }}
ul
  li(v-for='fact in facts') {{ fact.text }}
</template>

<script>
export default {
  props: ['msg'],
  data () {
    return {
      facts: [
        { text: 'Visually parsing Jade is wonderful.'},
        { text: 'Variables in Sass rock.'}
      ]
    }
  }
}
</script>
