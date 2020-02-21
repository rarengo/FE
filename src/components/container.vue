<template>
  <div class="app">
    <sidePanel></sidePanel>
  </div>
</template>

<script>
import sidePanel from "@/components/sidePanel.vue"
import mainpageMixin from "@/components/library/mainpageMixin"

export default {
  mixins: [ mainpageMixin ],
  components: {
    sidePanel
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
