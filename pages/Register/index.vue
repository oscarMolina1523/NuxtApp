<script>
import AppRegister from '~/components/AppRegister.vue'
import OptionLogin from '~/components/OptionLogin.vue'
export default {
  name: 'PageRegister',
  components: {
    AppRegister,
    OptionLogin
  }
}
</script>

<template>
  <div class="container">
    <AppRegister/>
    <OptionLogin/>
  </div>
</template>

<style scoped>
.container{
    width: 370px;
    text-align: center
}

:root {
    --font-family-system: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    --font-family-system-prism: 'Instagram Sans UI', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  }

  body {
    font-family: var(--font-family-system);
 }
</style>
