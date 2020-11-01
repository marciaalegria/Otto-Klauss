# otto_klauss
## instrucciones
```
Crear un proyecto Vue que implemente Vuex y Firestore para gestionar los productos de la
juguetería. Este proyecto debe estar enlazado con Firestore, por lo que debe crear una cuenta
en Google para ésto.
Crear una interfaz de acceso a usuarios. Sólo los usuarios registrados en el sistema de
autenticación de Firestore podrán ingresar al sistema. La validación debe realizarse por
dirección de correo y clave de Google.
Al validarse correctamente las credenciales de usuario en la interfaz de acceso, se debe
desplegar una interfaz principal donde se despliegue una tabla con el listado de juguetes en
stock. Esta interfaz además debe tener botones o enlaces de acceso a las interfaces necesarias
para agregar, eliminar y editar.
A la interfaz principal del punto anterior, se debe agregar un botón o enlace en cualquier sitio de
la página que, al hacerle click, cierre la sesión de firebase. Al cerrar la sesión, el usuario será
redirigido inmediatamente a la vista de acceso.
Como segunda etapa, usted deberá desarrollar los siguientes puntos:
En la interfaz de agregar juguetes, se debe desplegar un formulario donde se consideren los
siguientes campos:
Código (string)
Nombre del producto (string)
Stock (número)
Precio (número)
Al agregar el juguete a la base de datos de Firebase, se debe desplegar un modal, popup o alert que
nos pregunte si deseamos agregar dicho juguete, el cual tendrá 2 botones que serán Cancelar y
Aceptar. Si el usuario presiona Cancelar, el modal deberá desaparecer. En cambio si el usuario
presiona Aceptar, el sistema deberá agregar el registro en la base de datos de Firebase; al momento
de agregarse el registro, se debe actualizar la tabla de la interfaz principal y debe informarnos de que
el registro fue agregado. Esta interfaz debe contar con un botón que permita volver a la interfaz
principal.
Para eliminar juguetes, se debe desplegar un modal, popup o alert que nos pregunte si
deseamos eliminar dicho juguete, el cual tendrá 2 botones que serán Cancelar y Aceptar. Si el
usuario presiona Cancelar, el modal deberá desaparecer. En cambio si el usuario presiona
Aceptar, el sistema deberá eliminar el registro en la base de datos de Firebase; al momento de
eliminarse el registro, se debe actualizar la tabla de la interfaz principal y debe informarnos de
que el registro fue eliminado.
En la interfaz de editar juguetes, se debe desplegar una tabla con una lista de juguetes en stock
(stock > 0), donde se puedan editar los siguientes campos de un juguete:
Nombre (string)
Stock (número)
Precio (número)
Al editar el juguete a la base de datos de Firebase, se debe desplegar un modal, popup o alert que
nos pregunte si deseamos editar dicho juguete, el cual tendrá 2 botones que serán Cancelar y
Aceptar. Si el usuario presiona Cancelar, el modal deberá desaparecer. En cambio si el usuario
presiona Aceptar, el sistema deberá actualizar el registro correspondiente en la base de datos de
Firebase; al momento de actualizarse el registro, se debe actualizar la tabla de la interfaz principal y
debe informarnos de que el registro fue actualizado. Esta interfaz debe contar con un botón que
permita volver a la interfaz principal.
Con lo anterior listo, usted deberá compilar su proyecto en modo producción a Firebase Hosting.
Para almacenar en la base de datos de Firestore puede utilizar Axios para las llamadas entre la
aplicación y la base de datos.
Para el desarrollo de la interfaz de usuario, puede apoyarse en alguna librería como element-ui u otra
que haya visto a lo largo de las unidades anteriores.
Al finalizar, usted deberá entregar el código fuente de la aplicación desarrollada en un archivo
comprimido.
Además, debe compilar la aplicación en modo producción, desplegarla en Firebase y entregar en un
archivo de texto (al interior del archivo comprimido) el enlace a su aplicación en Firebase junto con un
usuario y clave para entrar al sistema. Este archivo se debe llamar “enlace-a-mi-firebaseapp.txt”.

Instrucciones
1. Crear proyecto Vue y Firebase, el cual esté disponible en Firebase Hosting. (1 punto)
2. Interfaz de acceso a usuarios (login). (1 punto)
3. Botón o enlace para cerrar sesión. (1 punto)
4. Interfaz principal con el listado de juguetes. (1 punto)
5. Interfaz para agregar juguetes al sistema. (2 puntos)
6. Interfaz para eliminar juguetes del sistema. (2 puntos)
7. Interfaz para editar juguetes registrados en el sistema. (2 puntos)
Código Nombre Stock Precio
A0001 Figura Cuphead 100 9990
A0002 Figura Max Steel 50 8990
A0003 Auto Hot Wheels 1000 1190
A0004 Cartas españolas 200 990
A0005 Cartas inglesas 200 1490
A0006 Furby 500 39990
Recursos
Listado inicial de productos a registrar en la base de datos:
Listado de Juguetes

```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
