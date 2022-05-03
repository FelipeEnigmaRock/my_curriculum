<template>
  <div class="home">
        
  </div>  
  <Informations />
  
</template>

<script>
import Navbar from "/src/components/Navbar.vue"
import Informations from "/src/components/Informations.vue"


export default {
  name: "Home",
  components: {
    Navbar,
    Informations
  }
}
</script>
<style scoped>
.home {
    background-color: red;
    height: 250px;
    display: flex;
    position: relative;
}
</style>

