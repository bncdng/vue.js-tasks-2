<template>
  <h1>Hallo Vue</h1>
  <MainHeader />
</template>

<script>
// IMPORT COMPONENT
import MainHeader from '@/components/MainHeader.vue'

export default {
  components: {
    // REGISTER COMPONENT
    MainHeader
  }
}
</script>
