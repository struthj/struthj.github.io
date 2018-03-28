<template>
  <div class="site-content">
    <navigation-bar/>
    <section class="section">
      <div class="container">
        <nuxt/>
      </div>
    </section>
    <contact-footer/>
  </div>
</template>

<script>
  import NavigationBar from "../components/NavigationBar";
  import ContactFooter from "../components/ContactFooter";
  export default {
    components: {
      NavigationBar,
      ContactFooter
    }
  }
</script>


<style>
  html, body {
    font-family: "Source Sans Pro", "Helvetica Neue", Arial, sans-serif;
  }
  
  .site-content {
    display: flex;
    min-height: 100vh;
    flex-direction: column;
  }

  .section {
    flex: 1;
  }




</style>