<template>
  <div class="hello">
    <!--Ligação de dados por meio da diretiva, ou seja está sendo realizado o data binding-->
    <h1>{{ msg }}</h1>
    <div>
      <!-- Interpolação: v-bind="" -->
      <span v-if="visibilidade">Olá</span>
    </div>
    </div>
</template>

<script>
/*Ela é exportada aqui para que seja possivel importar em outro arquivo*/
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    visibilidade: Boolean
  }
}
  /*Mas como passar valores para o nosso elemento? "visibilidade" */
  /**Apartir de momento que atribuir um valor false para visibilidade, não será mais impresso o olá */
//   data: {
//     visibilidade: false
//   }
// }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  color: green;
}

</style>