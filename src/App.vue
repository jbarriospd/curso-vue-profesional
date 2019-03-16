<template lang="pug">

  #app

    pm-header
    router-view
    pm-footer

</template>

<script>

import PmFooter from '@/components/layouts/Footer.vue'
import PmHeader from '@/components/layouts/Header.vue'

const tracks = [
  { name: "Dont stop me now", artist: "xxx" },
  { name: "Kilo", artist: "AeronSmith" },
  { name: "Lauerl", artist: "sssG" }
];
export default {
  name: "app",
  components: { PmFooter, PmHeader },
 

};
</script>

<style lang="scss">
@import "./sccs/main.scss";
.results {
  margin-top: 50px;
}
.is-active {
  border: 3px #23d160 solid;

}
</style>
