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
            <div class="icon-circulo icon-circulo--laranja">
              <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white" class="bi bi-map"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                  d="M15.817.113A.5.5 0 0 1 16 .5v14a.5.5 0 0 1-.402.49l-5 1a.502.502 0 0 1-.196 0L5.5 15.01l-4.902.98A.5.5 0 0 1 0 15.5v-14a.5.5 0 0 1 .402-.49l5-1a.5.5 0 0 1 .196 0L10.5.99l4.902-.98a.5.5 0 0 1 .415.103zM10 1.91l-4-.8v12.98l4 .8V1.91zm1 12.98 4-.8V1.11l-4 .8v12.98zm-6-.8V1.11l-4 .8v12.98l4-.8z" />
              </svg>
            </div>
            <h3 class="titulo-local texto-laranja"> Desenvolvimento</h3>
          </v-sheet>
        </v-col>
        <v-col cols="12" sm="4">
          <v-sheet class="bg-roxo d-flex flex-column justify-center align-center ma-2 pa-2">
            <div class="icon-circulo icon-circulo--rosa">
              <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white" class="bi bi-map"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                  d="M15.817.113A.5.5 0 0 1 16 .5v14a.5.5 0 0 1-.402.49l-5 1a.502.502 0 0 1-.196 0L5.5 15.01l-4.902.98A.5.5 0 0 1 0 15.5v-14a.5.5 0 0 1 .402-.49l5-1a.5.5 0 0 1 .196 0L10.5.99l4.902-.98a.5.5 0 0 1 .415.103zM10 1.91l-4-.8v12.98l4 .8V1.91zm1 12.98 4-.8V1.11l-4 .8v12.98zm-6-.8V1.11l-4 .8v12.98l4-.8z" />
              </svg>
            </div>
            <h3 class="titulo-local texto-rosa"> Espaço Conexão</h3>
          </v-sheet>
        </v-col>
        <v-col cols="12" sm="4">
          <v-sheet class="bg-roxo d-flex flex-column justify-center align-center ma-2 pa-2">
            <div class="icon-circulo icon-circulo--azul">
              <svg xmlns="http://www.w3.org/2000/svg" width="50" height="50" fill="white" class="bi bi-map"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                  d="M15.817.113A.5.5 0 0 1 16 .5v14a.5.5 0 0 1-.402.49l-5 1a.502.502 0 0 1-.196 0L5.5 15.01l-4.902.98A.5.5 0 0 1 0 15.5v-14a.5.5 0 0 1 .402-.49l5-1a.5.5 0 0 1 .196 0L10.5.99l4.902-.98a.5.5 0 0 1 .415.103zM10 1.91l-4-.8v12.98l4 .8V1.91zm1 12.98 4-.8V1.11l-4 .8v12.98zm-6-.8V1.11l-4 .8v12.98l4-.8z" />
              </svg>
            </div>
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

.icon-circulo > svg {
  width: 50px;
}

.icon-circulo {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
}

.icon-circulo--laranja {
  background-color: #FC671D;
}

.icon-circulo--rosa {
  background-color: #C42AEA;
}

.icon-circulo--azul {
  background-color: #0BC0D3;
}
</style>