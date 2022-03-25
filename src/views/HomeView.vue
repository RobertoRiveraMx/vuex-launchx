<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    
    <contador/>
    <cuadrado/>
    <botones/>
    
  </div>
</template>

<script>
import contador from "../components/contador.vue"
import cuadrado from "../components/cuadrado.vue"
import botones from "../components/botones.vue"

export default {
  name: 'HomeView', 
  components: {
    contador,
    cuadrado,
    botones
  }  
}
</script>

<style>

div{
  margin-bottom: 20px;
  margin-top: 20px;
}

.contador{

font-size: 80px;
}

.botones button{
  font-size: 40px;
  color: #35495E;
  width: 100px;
  margin: 0 10px;
  background-color: #41B883;
  border-color: #35495E;
  border-radius: 20px;
  margin-top: 20px;
}

.cuadrado{
  font-size: 25px;
}

</style>