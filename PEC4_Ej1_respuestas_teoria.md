## Explica qué hace cada uno de los siguientes comandos:

1. g new
Este comando sirve para crear un nuevo proyecto de angular, añadiendo al lado el nombre del proyecto. 

2. ng generate
Este comando sirve para añadir nuevos elementos al proyecto. Los elementos son los que se listan a continuación.

* component
Con ng generate component creamos un elemento html que tienen una función particular dentro de ese HTML. Puede ser una serie de etiquetas, un botón, un texto, etc. 

* directive
Cuando creamos una nueva directiva lo que hacemos es extender las funciones de nuestro archivo html. 

* Enum: Se utiliza para definir un conjunto de valores constantes nombrados.

* Guard: Protegen las rutas, es decir, controlan quién puede acceder a qué página de nuestra aplicación.

* Interface: Es la forma en que asignamos las propiedades o la estructura que van a tener nuestros objetos en typescript. 
Son como los planos de una casa. Definen cómo deberían lucir tus datos. Por ejemplo, podemos crear una interfaz que especifique qué propiedades debe tener cada usuario (como nombre, correo electrónico, etc.).

* Pipe: Lo utilizamos para poder manipular y modificar datos antes de mostrarlos en la interfaz. 

* Service: Contienen toda la lógica de la aplicación que no está relacionada con la vista. Nos sirve para agrupar todas las operaciones que vamos a usar en nuestra aplicación para poder reutilizarla en cualquier parte. 

3. ng serve
Este comando inicia el servidor de desarrollo de Angular.

4.  ng test
Este comando lo utilizamos para ejecutar pruebas unitarias en la aplicación Angular, de manera que podemos ver si funciona correctamente nuestro código. 

5. ng version: Este comando te muestra la versión de Angular CLI que se está utilizando en nuestro proyecto, así como la versión de Angular Core que estamos usando. 