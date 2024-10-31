<template>
  <ion-page>
    <ion-header :translucent="true">
      <ion-toolbar>
        <ion-title>Veterinaria</ion-title>
      </ion-toolbar>
    </ion-header>

    <ion-content class="ion-padding">
      <!-- Barra de búsqueda -->
      <ion-searchbar show-cancel-button="always" placeholder="Contenidos"></ion-searchbar>

      <!-- Botones de Iniciar Sesión y Registro -->
      <div class="button-group">
        <ion-button id="present-alert">Iniciar sesión</ion-button>
        <ion-button id="present-alert" color="secondary">Registrarse</ion-button>
      </div>

      <!-- Campos de entrada de datos del usuario -->
      <ion-input label="Nombre" placeholder="Ingrese su nombre"></ion-input>
      <ion-input label="Apellido" placeholder="Ingrese su apellido"></ion-input>
      <ion-input label="Teléfono" type="tel" placeholder="888-888-8888"></ion-input>

      <!-- Campo de Email -->
      <ion-list>
        <ion-item>
          <ion-input label-placement="floating" placeholder="correo@example.com">
            <div slot="label">Email</div>
          </ion-input>
        </ion-item>
      </ion-list>

      <!-- Campo de Contraseña -->
      <ion-input type="password" label="Contraseña" placeholder="Ingrese su contraseña">
        <ion-input-password-toggle slot="end"></ion-input-password-toggle>
      </ion-input>

      <!-- Campo de Motivo de Consulta -->
      <ion-item>
        <ion-input
          label="Motivo de consulta"
          label-placement="stacked"
          :clear-input="true"
          placeholder="Comente acá su motivo de consulta"
        >
        </ion-input>
      </ion-item>

      <!-- Grid de ejemplo -->
      <ion-grid>
        <ion-row>
          <ion-col>1</ion-col>
          <ion-col>2</ion-col>
          <ion-col>3</ion-col>
          <ion-col>4</ion-col>
          <ion-col>5</ion-col>
        </ion-row>
      </ion-grid>

      <!-- Contenedor de enlaces adicionales -->
      <div id="container">
        <strong></strong>
        <p>
          
          <a target="_blank" rel="noopener noreferrer" href="https://ionicframework.com/docs/components"></a>.
        </p>
      </div>
    </ion-content>
  </ion-page>
</template>

<script setup lang="ts">
import {
  IonContent,
  IonHeader,
  IonPage,
  IonTitle,
  IonToolbar,
  IonSearchbar,
  IonButton,
  IonInput,
  IonList,
  IonItem,
  IonText,
  IonGrid,
  IonRow,
  IonCol,
} from '@ionic/vue';
</script>

<style scoped>
.button-group {
  display: flex;
  justify-content: space-between;
  margin-top: 16px;
}

#container {
  text-align: center;
  position: absolute;
  left: 0;
  right: 0;
  top: 50%;
  transform: translateY(-50%);
}

#container strong {
  font-size: 20px;
  line-height: 26px;
}

#container p {
  font-size: 16px;
  line-height: 22px;
  color: #8c8c8c;
  margin: 0;
}

#container a {
  text-decoration: none;
  color: #3880ff;
}
</style>
