<template>
  <div class="about">
      <div class="sign">
        <form class="auth" action="">
            <h1>Регистрация</h1>
            <div class="block1">
              <span>Логин</span><br>
              <input class="inp"><br>
            </div>

            <div class="block1">
              <span>E-mail</span><br>
              <input class="inp"><br>
            </div>

            <div class="block1">
              <span>Пароль</span><br>
              <input class="inp"><br>
            </div>

            <div class="block1">
            <span>Повторите</span><br>
            <input class="inp"><br>
            </div>

            <button class="reg-button">Зарегистрироваться</button>
        </form>
      </div>
  </div>
</template>

<style lang="scss">
.auth{
  padding: 10px;
}
.sign {
    display: flex;
    justify-content: center;
    align-items: center;
}
.inp{
    padding: 5px;
}
.block1{
  padding: 5px;
  padding-bottom: 10px;
}
.inp_pass{
    padding-bottom: 40px;
}
.reg-button{
    margin-top: 10px;
    width: 100%;
    padding: 15px;
    border: 0;
    font-size: 16px;
    color:white;
    background-color: blue;
}
</style>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
