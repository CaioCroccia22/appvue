<template>
  <div class="hello">
    <!--Ligação de dados por meio da diretiva, ou seja está sendo realizado o data binding-->

    <h1>{{ msg }}</h1>
    <div>
      <span>Olá</span>
    </div>
    </div>
</template>

<script>
/*Ela é exportada aqui para que seja possivel importar em outro arquivo*/
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: green;
}

</style>