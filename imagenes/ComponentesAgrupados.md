![Componente agrupado 1](crud.png)
 <!-- Grupo de Contacto de Emergencia -->
 ''
    <ion-list class="emergency-contact">
      <ion-item>
        <ion-input label="Nombre de Contacto de Emergencia" placeholder="Nombre del contacto"></ion-input>
      </ion-item>
      <ion-item>
        <ion-input label="Teléfono de Emergencia" type="tel" placeholder="888-888-8888"></ion-input>
      </ion-item>
    </ion-list>

![Componente agrupado 2](crud2.png)
 <!-- Grupo de Detalles de Mascota -->
 ''
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
  

![Componente agrupado 3](crud3.png)
<!-- Grupo de Selección de Servicios -->
''
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