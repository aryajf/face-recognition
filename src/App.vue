<template>
  <div>
    <router-view/>
    <footers/>
  </div>
</template>

<script>
import Footers from '@/components/Footers.vue'
export default {
  components: {
    Footers
  },
}
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap');

html, body{
  font-family: 'Roboto', sans-serif;
}

::-moz-selection { /* Code for Firefox */
  color: #eee;
  background: #E91E63;
}

::selection {
  color: #eee;
  background: #E91E63;
}

/* Works on Firefox */
* {
  scrollbar-width: thin;
  scrollbar-color: #EC407A #eee;
}

/* Works on Chrome, Edge, and Safari */
*::-webkit-scrollbar {
  width: 12px;
}

*::-webkit-scrollbar-track {
  background: #eee;
}

*::-webkit-scrollbar-thumb {
  background-color: #EC407A;
  border-radius: 20px;
  border: 3px solid #eee;
}
</style>
