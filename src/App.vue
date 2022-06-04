<template>
  <NavBanner/>
  <router-view/>
</template>

<script>
// @ is an alias to /src
import NavBanner from '@/components/NavBanner.vue'

export default {
  components: {
    NavBanner
  }
}
</script>

<style>
:root{
  --colorbg1: #0B0C10;
  --colorbg2: #202833;
  --color1: #C8C3C5;
  --color2: #66FCF1;
  --color3: #46A29F;

  background-color: var(--colorbg1);

}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--color1);
  background-color: var(--colorbg1);
}
</style>
