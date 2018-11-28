<template>
  <span>

    <login-template>

    <span slot="menuesquerdo">
      <img src="https://static.quizur.com/i/b/5b035c77702c13.471891555b035c775c3ff9.54480388.png" class="responsive-img">
    </span>

<span slot="principal">

  <span v-if="!cadastro">
    <h2>Login</h2>

    <input type="text" placeholder="E-mail" value="">
    <input type="text" placeholder="Senha" value="">
    <button class="btn">Entrar</button>
    <router-link class="btn orange"to="/cadastro">Cadastre-se</router-link>
  </span>

</span>


    </login-template>



 </span>

</template>

<script>
import LoginTemplate from '@/templates/LoginTemplate'


export default {
  name: 'Login',
  data () {
    return {

    }
  },
  components:{
    LoginTemplate
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
