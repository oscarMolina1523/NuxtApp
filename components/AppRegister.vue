<script>
export default {
  methods: {
    redirectHome () {
      this.$router.push('/Home')
    }
  }
}
</script>

<template>
    <div class="form">
        <img class="img-header" src="https://akm-img-a-in.tosshub.com/businesstoday/images/story/202212/instagram-users-irked-with-the-new-update-sixteen_nine.jpg?size=1200:675" alt="this is the header">
        <br>
        <span class="message">Registrate para ver fotos y videos de tus amigos</span>
        <br>
        <button>Iniciar sesion con Facebook</button>
        <br>
        <img class="img-divisor" src="../content/opcion.png" alt="divisor">
        <br>
        <input placeholder="Numero movil o correo electronico"/>
        <input placeholder="Nombre completo"/>
        <input placeholder="Nombre de usuario"/>
        <input placeholder="Contrasena"/>
        <br>
        <div class="privacity-container">
            <span class="privacity">Es posible que los usuarios de nuestro servicio hayan subido tu
                información de contacto en Instagram. Más información</span>
        </div>
        <div class="privacity-container">
            <span class="privacity">Al registrarte, aceptas nuestras Condiciones,
                nuestra Política de privacidad y nuestra Política de cookies.</span>
        </div>
        <br>
        <button @click="redirectHome()" id="register-button">Registrarte</button>
    </div>
</template>

<style>
.img-header{
    height: 100px;
    margin-left: 10px;
}

.img-divisor{
  height: 40px;
  margin-left: 10px
}

.form{
    border: 1px solid #ccc;
    height: 660px;
    margin-bottom: 10px
}

button{
    background-color: rgb(0 149 246);;
    height: 35px;
    width: 80%;
    border-radius: 10px;
    margin-top: 5px;
    margin-bottom: 10px;
    color: white;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

input {
  width: 80%;
  margin-left: 5px;
  height: 40px;
  border-radius: 2px;
  background-color: rgb(246, 244, 244);
  border: 1px solid #ccc;
  padding-left: 5px;
  outline: none;
  margin-top: 5px;
  margin-bottom: 5px;
  font-size: 12px;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}
.message{
    color: rgb(115 115 115);
    margin-left: 10px;
    margin-right: 10px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

.privacity-container{
    width: 80%;
    margin-left: 40px;
    margin-bottom: 20px;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

.privacity{
    color: rgb(115 115 115);
    font-size: 12px;
    text-align: justify;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}
</style>
