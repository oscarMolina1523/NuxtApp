<template>
    <div class="container">
      <div class="left-panel">
        <ShowPhone/>
      </div>
      <div class="right-panel">
        <AppLogin/>
        <OptionRegister/>
      </div>
    </div>
</template>

<script>
import AppLogin from '../components/AppLogin.vue'
import OptionRegister from '../components/OptionRegister.vue'
import ShowPhone from '../components/ShowPhone.vue'
export default {
  name: 'HomePage',
  components: {
    AppLogin, OptionRegister, ShowPhone
  }
}
</script>

<style scoped>
  h1{
    font-weight: bold;
  }

  .container {
    display: flex;
    height: 590px;
    width: 1100px;
  }
  .left-panel {
    flex: 1;
    background-color: white;
  }

  .right-panel {
    flex: 1;
    background-color: white;
  }

  :root {
    --font-family-system: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    --font-family-system-prism: 'Instagram Sans UI', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  }

  body {
    font-family: var(--font-family-system);
  }
</style>
