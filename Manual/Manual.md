## Componentes 


# Barra de búsqueda 
```js
      <ion-searchbar show-cancel-button="always" placeholder="Contenidos"></ion-searchbar>
 ```

# Botones de Iniciar Sesión y Registro
```js 
      <div class="button-group">
        <ion-button id="present-alert">Iniciar sesión</ion-button>
        <ion-button id="present-alert" color="secondary">Registrarse</ion-button>
      </div>

 ```

# Campos de entrada de datos del usuario 
```js
      <ion-input label="Nombre" placeholder="Ingrese su nombre"></ion-input>
      <ion-input label="Apellido" placeholder="Ingrese su apellido"></ion-input>
      <ion-input label="Teléfono" type="tel" placeholder="888-888-8888"></ion-input>
```

# Campo de Email 
```js
      <ion-list>
        <ion-item>
          <ion-input label-placement="floating" placeholder="correo@example.com">
            <div slot="label">Email</div>
          </ion-input>
        </ion-item>
      </ion-list>
```

# Campo de Contraseña 
```js
      <ion-input type="password" label="Contraseña" placeholder="Ingrese su contraseña">
        <ion-input-password-toggle slot="end"></ion-input-password-toggle>
      </ion-input>
```

# Campo de Motivo de Consulta 
```js
      <ion-item>
        <ion-input
          label="Motivo de consulta"
          label-placement="stacked"
          :clear-input="true"
          placeholder="Comente acá su motivo de consulta"
        >
        </ion-input>
      </ion-item>
```

# Grid de ejemplo 
```js
      <ion-grid>
        <ion-row>
          <ion-col>1</ion-col>
          <ion-col>2</ion-col>
          <ion-col>3</ion-col>
          <ion-col>4</ion-col>
          <ion-col>5</ion-col>
        </ion-row>
      </ion-grid>
```

## Componentes Agrupados

# Grupo de Contacto de Emergencia 
```js
    <ion-list class="emergency-contact">
      <ion-item>
        <ion-input label="Nombre de Contacto de Emergencia" placeholder="Nombre del contacto"></ion-input>
      </ion-item>
      <ion-item>
        <ion-input label="Teléfono de Emergencia" type="tel" placeholder="888-888-8888"></ion-input>
      </ion-item>
    </ion-list>
```

# Grupo de Detalles de Mascota 
 ```js
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
```
# Grupo de Selección de Servicios 
```js
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
```