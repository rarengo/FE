<template>
  <div class="app">
    <mainpage></mainpage>
  </div>
</template>

<script>
import mainpage from "@/components/mainContainer.vue"
import mainpageMixin from "@/components/library/mainpageMixin"

export default {
  mixins: [ mainpageMixin ],
  components: {
    mainpage
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
