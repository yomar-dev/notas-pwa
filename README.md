# Notas PWA

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.8.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).



### Nota

Luego de crear el proyecto para poder agregar el **Service Worker** debemos hacerlo de la siguiente manera:
`ng add @angular/pwa --project nombre-del-proyecto` <br><br>.

**Correr nuestra app en modo de producción:** `ng build --prod` <br>
**Libreria para crear servidor:** `sudo npm install -g http-server` <br>


### Crear un servidor para nuestra App:

1) Ir al directorio **dist** (`cd dist/nombre-app`) <br>
2) Ejecutar el comando `http-server` <br>



## Service Worker:

-Son un archivo mas. <br>
- Están escritos en JS. <br>
- Funcionan como un proxy, es decir que interceptan las llamadas en red. Esto es muy importante para las PWA porque te permite mostrar información a tus usuarios sin necesidad de tener internet. <br>
- Se detienen cuándo no están en uso. <br>
- Solo funcionan sobre HTTPS. <br>
- Sus métodos están basados en promesas.<br>


### Ventajas:

**Confiabilidad:** Provee recursos estáticos, dinámicos y extensos desde caché. <br>
**Performance:** Solamente hace llamados remotos cuando es necesario. <br>
**Push notifications:** Notificaciones push para re-atraer a tus usuarios. <br>
> Te permite crear tu propio sistema de caching.

### Ejecutar script para mandar nuestra App a producción y leventar nuestro servidor.
`npm run build:server` <br>

**Instalar Angular Material:** `npm install --save @angular/material @angular/cdk` <br>
**Instalar animaciones para Angular Material:** `npm install --save @angular/animations` <br>


### Enlaces de interes:

[Web App Manifest Generator](https://app-manifest.firebaseapp.com/) <br>
[Documentación Angular Material](https://material.angular.io/) <br>