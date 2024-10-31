![componente 1](1.png)

 <ion-content class="ion-padding">
      <!-- Barra de búsqueda -->
      <ion-searchbar show-cancel-button="always" placeholder="Contenidos"></ion-searchbar>

![componente 2](2.png)

![componente 3](3.png)

<!-- Botones de Iniciar Sesión y Registro -->
''
      <div class="button-group">
        <ion-button id="present-alert">Iniciar sesión</ion-button>
        <ion-button id="present-alert" color="secondary">Registrarse</ion-button>
      </div>

![componente 4](4.png)

![componente 5](5.png)

![componente 6](6.png)

<!-- Campos de entrada de datos del usuario -->
''
      <ion-input label="Nombre" placeholder="Ingrese su nombre"></ion-input>
      <ion-input label="Apellido" placeholder="Ingrese su apellido"></ion-input>
      <ion-input label="Teléfono" type="tel" placeholder="888-888-8888"></ion-input>

![componente 7](7.png)
<!-- Campo de Email -->
''
      <ion-list>
        <ion-item>
          <ion-input label-placement="floating" placeholder="correo@example.com">
            <div slot="label">Email</div>
          </ion-input>
        </ion-item>
      </ion-list>


![componente 8](8.png)
 <!-- Campo de Contraseña -->
 ''
      <ion-input type="password" label="Contraseña" placeholder="Ingrese su contraseña">
        <ion-input-password-toggle slot="end"></ion-input-password-toggle>
      </ion-input>

![componente 9](9.png)
<!-- Campo de Motivo de Consulta -->
''
      <ion-item>
        <ion-input
          label="Motivo de consulta"
          label-placement="stacked"
          :clear-input="true"
          placeholder="Comente acá su motivo de consulta"
        >
        </ion-input>
      </ion-item>

![componente 10](10.png)
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