<script>
export default {
  methods: {
    redirectLogin () {
      this.$router.push('/')
    }
  }
}
</script>

<template>
    <div class="container-login">
        <span>¿Tienes una cuenta? <span class="redirect" @click="redirectLogin()">Entrar</span></span>
    </div>
</template>

<style scoped>
.container-login{
    margin-top: 5px;
    height: 50px;
    text-align: center;
    border: 1px solid #ccc;
    padding-top: 20px;
}

span{
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}
</style>
