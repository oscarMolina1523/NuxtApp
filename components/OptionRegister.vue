<script>
export default {
  methods: {
    redirectRegister () {
      this.$router.push('/Register')
    }
  }
}
</script>

<template>
    <div class="container-register">
        <span>¿No tienes una cuenta? <span class="redirect" @click="redirectRegister()">Registrate</span></span>
    </div>
</template>

<style>
.container-register{
    margin-right: 140px;
    margin-top: 10px;
    margin-left: 20px;
    margin-bottom: 10px;
    height: 12%;
    text-align: center;
    border: 1px solid #ccc;
    padding-top: 20px;
}

.redirect{
    color: #0095f6;
    font-weight: bold;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

span{
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}
</style>
