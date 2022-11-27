<template>
  <Apartment />
</template>

<script lang="ts">
import Vue from 'vue'
import Apartment from "../components/apartments/Apartment.vue"

export default Vue.extend({
  name: 'IndexPage',
  components: {
    Apartment
  },
})
</script>
