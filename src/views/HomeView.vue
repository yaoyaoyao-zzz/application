<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <layout/>
  </div>
</template>

<script>
// @ is an alias to /src
import layout from '@/components/layout/layout.vuee'

export default {
  name: 'HomeView',
  components: {
    layout
  }
}
</script>
