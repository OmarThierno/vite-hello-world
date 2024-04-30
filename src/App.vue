<script>
  import AppTitle from './components/AppTitle.vue';
  export default{
    components: {
      AppTitle,
    },
    data() {
      return{
        greeting: 'Hello'
      }
    }
  }
</script>

<template>
  <AppTitle />
  <h2>{{ greeting }}</h2>
</template>

<style>

</style>
