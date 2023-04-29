<template>
  <v-app theme="">
    <v-app-bar flat class="border-b">
      <v-app-bar-title> Formato Certo </v-app-bar-title>
      <v-bottom-navigation :elevation="5" grow>
        <v-btn value="somos"> Quem somos </v-btn>
        <v-btn value="valores"> valores </v-btn>
        <v-btn value="localizacao"> localizaçãoa </v-btn>
      </v-bottom-navigation>
    </v-app-bar>

    <v-main>
      <v-container>
        <div>
          <div>
            <v-carousel show-arrows="hover">
              <v-carousel-item
                img
                src="https://i.pinimg.com/564x/57/a3/78/57a378c88099a6366e5bff1b9d5f125d.jpg"
                cover
              >
              </v-carousel-item>
              <v-carousel-item src="imagens/imagemteste2.jpg" cover>
              </v-carousel-item>
              <v-carousel-item src="imagens/imagemteste3.jpg" cover>
              </v-carousel-item>
            </v-carousel>
          </div>
          <div id="card" class="d-flex justify-space-evenly ">
            <v-card title="MAQUINAS" text="A" variant="outlined"></v-card>
            <v-card title="CONTROLE" text="..." variant="outlined"></v-card>
            <v-card title="ATUANDO EM" text="..." variant="outlined"></v-card>
          </div>
          <div class="">
            <h1>QUEM SOMOS</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam
              blanditiis hic enim officia dicta iure sapiente commodi. Tempore
              ratione reiciendis pariatur eligendi, quod impedit, cumque quo
              laudantium exercitationem iusto mollitia.aaaa
            </p>
          </div>

        </div>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup></script>

<style scoped>
h1 {
  text-align: center;
}
.v-card {
height: 150px;
width: 250px;
margin-top: 50px;
margin-bottom: 50px;
}
</style>
