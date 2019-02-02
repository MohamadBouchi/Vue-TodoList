<template lang="pug">
  div#app
    Header
    div#nav
      router-view
</template>

<script>
import Header from './components/layout/Header'
export default {
  name: "app",
  components: {
    Header
  }
}
</script>
