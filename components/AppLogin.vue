<script>
export default {
  name: 'AppLogin'
}
</script>

<template>
    <div class="container-login">
        <img class="img-header" src="https://akm-img-a-in.tosshub.com/businesstoday/images/story/202212/instagram-users-irked-with-the-new-update-sixteen_nine.jpg?size=1200:675" alt="this is the header">
        <input placeholder="Telefono, usuario o correo electronico"/>
        <input placeholder="Contrasena"/>
        <br>
        <button>Entrar</button>
        <br>
        <div class="facebook">
            <img class="img-divisor" src="../content/opcion.png" alt="divisor">
            <br>
            <img class="facebookIcon" src="https://coresight.com/wp-content/uploads/2019/01/facebook.png" alt="facebook imagen"/>
        <span class="login-Facebook">Iniciar sesion con Facebook</span>
        </div>
        <br>
        <br>
        <span class="change-password">¿Has olvidado la contrasena?</span>
    </div>
</template>

<style scoped>
.container-login{
    margin-right: 140px;
    margin-top: 10px;
    margin-left: 20px;
    margin-bottom: 10px;
    height: 75%;
    text-align: center;
    border: 1px solid #ccc;
}

.img-header{
    height: 100px;
    margin-left: 10px
}

input {
  width: 70%;
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

.img-divisor{
  height: 40px;
  margin-left: 10px
}

.facebookIcon{
    height: 20px;
    width: 20px;
    margin-left: 10px
}

.facebook{
    background-color: transparent
}

button{
    background-color: #4cb5f9;
    height: 35px;
    width: 70%;
    border-radius: 10px;
    margin-top: 10px;
    margin-bottom: 10px;
    color: white;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

.login-Facebook{
    color: #385185;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}

.change-password{
    font-size: 12px;
    color: #385185;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
}
</style>
