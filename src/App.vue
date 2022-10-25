<template>
  <TheNavbar/>
  <router-view/>
</template>
<script>
import TheNavbar from '@/components/TheNavbar.vue'
export default {
  components: {
    TheNavbar
  }
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;700;800&display=swap');
/* font-family: 'Inter', sans-serif; */

*, *::before, *::after {
  box-sizing: border-box;
}
* {
  margin: 0;
}
html, body {
  height: 100%;
  font-size: 15px;
}
body {
  line-height: 1.5;
  -webkit-font-smoothing: antialiased;
}
img, picture, video, canvas, svg {
  display: block;
  max-width: 100%;
}
input, button, textarea, select {
  font: inherit;
}
p, h1, h2, h3, h4, h5, h6 {
  overflow-wrap: break-word;
}
#root, #__next {
  isolation: isolate;
}

:root{
  /* neutral */
  --bg: hsl(36, 100%, 99%);
  --grayishblue: hsl(233, 8%, 79%);
  --darkgrayblue: hsl(236, 13%, 42%);
  --verydarkblue: hsl(240, 100%, 11%);

  /* primary */
  --softorange: hsl(35, 77%, 62%);
  --softred: hsl(5, 85%, 63%);
}
</style>
