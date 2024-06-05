<template>
  <ion-page>
    <ion-header :translucent="true" style="--ion-background-color: #f5f5f5;">
      <ion-toolbar>
        <ion-title style="color: #004b89;">Impacto da IA</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content :fullscreen="true" style="--ion-background-color: #f5f5f5;">
      <div id="container">
        <p class="blue-box">A inteligência artificial está transformando rapidamente o mercado de trabalho em todo o mundo. Aqui estão algumas maneiras pelas quais isso está acontecendo:</p>

        <h2 style="color: #000; font-weight: bold;">Automação de Tarefas</h2>
        <p class="blue-box">Com o avanço da inteligência artificial e da automação, muitas tarefas repetitivas e rotineiras estão sendo realizadas por máquinas e algoritmos. Isso pode levar à redução da demanda por trabalhadores em certas áreas.</p>

        <h2 style="color: #000; font-weight: bold;">Criação de Novas Oportunidades</h2>
        <p class="blue-box">A inteligência artificial também está criando novas oportunidades de emprego em áreas como ciência de dados, aprendizado de máquina, desenvolvimento de IA e análise de dados. Profissionais com habilidades nessas áreas estão em alta demanda.</p>

        <h2 style="color: #000; font-weight: bold;">Requalificação Profissional</h2>
        <p class="blue-box">Para lidar com as mudanças no mercado de trabalho causadas pela inteligência artificial, muitos trabalhadores estão buscando requalificação profissional. Isso pode envolver aprender novas habilidades ou aprimorar habilidades existentes para se adaptar às novas demandas do mercado.</p>

        <h2 style="color: #000; font-weight: bold;">Desafios e Oportunidades</h2>
        <p class="blue-box">Embora a inteligência artificial possa trazer desafios, também oferece oportunidades significativas para aumentar a eficiência, a produtividade e a inovação em diversos setores. É importante que governos, empresas e indivíduos estejam preparados para lidar com essas mudanças e maximizar os benefícios da IA no mercado de trabalho.</p>
        
        <p>Comece com o Ionic <a target="_blank" rel="noopener noreferrer" href="https://ionicframework.com/docs/components">UI Components</a></p>
      </div>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import { IonContent, IonHeader, IonPage, IonTitle, IonToolbar } from '@ionic/vue';
</script>

<style scoped>
#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

.blue-box {
  background-color: #e3f2fd;
  padding: 10px;
  border-radius: 5px;
  color: #000;
}

#container h2 {
  font-size: 24px;
  margin-top: 20px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #000;
  margin: 0;
}

#container a {
  text-decoration: none;
  color: #007bff;
}

ion-content {
  --background: #f5f5f5;
}
</style>
