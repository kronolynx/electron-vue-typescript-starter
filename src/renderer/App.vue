
<template lang="pug">
  #app Basic pug {{ msg }}
    #nav 
      router-link(to="/") Home
      |  |  
      router-link(to="/counter") Counter 
    router-view
</template>


<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {
      msg: "boilerplate"
    }
  }
})
</script>

