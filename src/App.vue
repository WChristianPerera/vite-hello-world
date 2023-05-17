<script>
  import AppTitle from "./components/AppTitle.vue"
  import AppParagraph from "./components/AppParagph.vue"
  export default{
    components: {
      AppTitle,
      AppParagraph,
    }
  }
</script>


<template>
  <AppTitle/>
  <AppParagraph/>  

</template>


<style scoped>
  body{
    background-color: black;
  }
  h1{
    color: red;
  }
  p{
    font-size: larger;
  }

</style>