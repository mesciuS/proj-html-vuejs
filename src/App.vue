<script>
import '@fortawesome/fontawesome-free/css/all.css'
import AppHeader from "./components/AppHeader.vue"
import AppMain1 from "./components/AppMain1.vue"
import AppFooter from "./components/AppFooter.vue"
export default {
  data() {
    return {

    }
  },

  components: {
    AppHeader,
    AppMain1,
    AppFooter,
  },
}
</script>

<template>
  <AppHeader></AppHeader>
  <AppMain1></AppMain1>
  <AppFooter></AppFooter>
</template>

<style lang="scss" scoped>

</style>
