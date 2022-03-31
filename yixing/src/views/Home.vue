<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
  </div> -->
  <Menu />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Menu from '../components/Menu.vue'
export default defineComponent({
  name: 'Home',
  components: {
    Menu
  }
})
</script>
