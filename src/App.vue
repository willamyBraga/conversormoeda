<template>
  <div id="app">
    <h1 class="text-center">Conversor de Moedas</h1>
    <div class="linha">
      <Conversor moeda-a="USD" moeda-b="BRL" />
      <Conversor moeda-a="BRL" moeda-b="USD" />
    </div>
       <div class="linha">
      <Conversor moeda-a="CAD" moeda-b="BRL" />
      <Conversor moeda-a="BRL" moeda-b="CAD" />
    </div>
       <div class="linha">
      <Conversor moeda-a="EUR" moeda-b="BRL" />
      <Conversor moeda-a="BRL" moeda-b="EUR" />
    </div>
        
  </div>
</template>

<script>
import Conversor from './components/Conversor';
export default {
  name: 'App',
  components: {
   Conversor
  }
}
</script>

<style>
  #App{
    font-family: "Avanir", Arial, Helvetica, sans-serif;
    color: #2c3e60;
    margin-top: 60px;
    max-width: 900px;
    margin: auto;
  }
  .linha{
    margin-top: 40px;
    display: flex;
    margin: auto;
    justify-items: center;
    align-items: center;
    justify-content: center;
    margin: 10px 10px 10px 10px;
  }
  .text-center{
    text-align: center;
  }
  body{
   background: linear-gradient(0.25turn, #3f87a6, #ebf8e1, #f69d3c);

  }
  </style>
