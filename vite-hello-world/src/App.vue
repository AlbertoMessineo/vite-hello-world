<script>
/**
 * 1. importare il componente
 * 2. registrare il componente
 * 3. uso del componente nel template
 */
import AppTitle from './components/AppTitle.vue';

export default {
  name: 'App',
  components: {
    AppTitle,
  }
}
</script>

<template>
  <div>
    <AppTitle />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
