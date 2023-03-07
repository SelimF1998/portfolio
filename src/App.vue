<script setup>
import Navbar from './components/Navbar.vue'
import Three from './components/Three.vue'

</script>

<template>
  <div>
    <Navbar />
    <Three />
  </div>
  
</template>

<script>
export default {
    name: "App",
    components: {
      Navbar,
      Three,

    }
    
}
</script>


