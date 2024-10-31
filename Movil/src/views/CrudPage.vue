<template>
    <!-- Grupo de Contacto de Emergencia -->
    <ion-list class="emergency-contact">
      <ion-item>
        <ion-input label="Nombre de Contacto de Emergencia" placeholder="Nombre del contacto"></ion-input>
      </ion-item>
      <ion-item>
        <ion-input label="Teléfono de Emergencia" type="tel" placeholder="888-888-8888"></ion-input>
      </ion-item>
    </ion-list>
  
    <!-- Grupo de Detalles de Mascota -->
    <ion-list class="pet-details">
      <ion-item>
        <ion-input label="Nombre de Mascota" placeholder="Nombre de la mascota"></ion-input>
      </ion-item>
      <ion-item>
        <ion-select label="Tipo de Mascota" placeholder="Selecciona uno">
          <ion-select-option value="perro">Perro</ion-select-option>
          <ion-select-option value="gato">Gato</ion-select-option>
          <ion-select-option value="otro">Otro</ion-select-option>
        </ion-select>
      </ion-item>
      <ion-item>
        <ion-input label="Edad de la Mascota" type="number" placeholder="Edad en años"></ion-input>
      </ion-item>
    </ion-list>
  
    <!-- Grupo de Selección de Servicios -->
    <ion-list class="service-selection">
      <ion-item>
        <ion-select label="Servicio Necesitado" placeholder="Seleccione un servicio">
          <ion-select-option value="consulta">Consulta</ion-select-option>
          <ion-select-option value="vacunacion">Vacunación</ion-select-option>
          <ion-select-option value="urgencias">Urgencias</ion-select-option>
        </ion-select>
      </ion-item>
    </ion-list>
  </template>
  
  <style scoped>
  /* Estilos de color para los grupos */
  .emergency-contact {
    background-color: #d0ebff; /* Azul claro para Contacto de Emergencia */
    padding: 16px;
    border-radius: 8px;
    margin-bottom: 16px;
  }
  
  .pet-details {
    background-color: #b3d7ff; /* Azul más oscuro para Detalles de Mascota */
    padding: 16px;
    border-radius: 8px;
    margin-bottom: 16px;
  }
  
  .service-selection {
    background-color: #99c2ff; /* Azul más intenso para Selección de Servicios */
    padding: 16px;
    border-radius: 8px;
    margin-bottom: 16px;
  }
  
  /* Espaciado adicional y estilización */
  ion-item {
    margin: 8px 0;
  }
  </style>
  