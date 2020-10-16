<template>
  <div>
    <NavBar/>
    <main>
      <div class="container">
        <Nuxt />
      </div>
    </main>
  </div>
</template>
<script>
  import { NavBar } from "@/components/NavBar";
  export default {
    components: {
      NavBar
    }
  }
</script>