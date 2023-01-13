<template>
  <div class="mt-40 fundo bg-roxo">
    <v-container>
      <v-row class="d-flex flex-column justify-center align-center">
        <v-img width="150" src="./assets/logo.png"></v-img>
        <h1 class="text-white">Bem-vindo, <span class="texto-rosa">digilover!</span></h1>
      </v-row>
      <v-row>
        <v-col cols="12" sm="4">
          <v-sheet class="bg-roxo d-flex flex-column justify-center align-center ma-2 pa-2">
            <v-img width="150" :aspect-ratio="1" src="./assets/desenvolvimento.png" cover></v-img>
            <h3 class="titulo-local texto-laranja"> Desenvolvimento</h3>
          </v-sheet>
        </v-col>
        <v-col cols="12" sm="4">
          <v-sheet class="bg-roxo d-flex flex-column justify-center align-center ma-2 pa-2">
            <v-img width="150" :aspect-ratio="1" src="./assets/espacoConexao.png" cover></v-img>
            <h3 class="titulo-local texto-rosa"> Espaço Conexão</h3>
          </v-sheet>
        </v-col>
        <v-col cols="12" sm="4">
          <v-sheet class="bg-roxo d-flex flex-column justify-center align-center ma-2 pa-2">
            <v-img width="150" :aspect-ratio="1" src="./assets/salaReuniao.png" cover></v-img>
            <h3 class="titulo-local texto-azul"> Sala de Reunião</h3>
          </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script setup>

</script>

<style>
@media screen and (min-width:600px) {
  .fundo {
    height: 100vh;
  }
}

.fundo {
  width: 100vw;
  padding-top: 40px;
}

.bg-roxo {
  background-color: #2C006A !important;
}

.titulo-local {
  padding: 2px;
  font-size: 30px;
  font-weight: bold;
}

.texto-laranja {
  color: #FC671D;
}

.texto-azul {
  color: #0BC0D3;
}

.texto-rosa {
  color: #C42AEA;
}
</style>