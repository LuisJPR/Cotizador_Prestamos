# Cotizador_Prestamos
Link del proyecto: https://cotizadorprestamos-luisjpr.netlify.app/
##  Que es React
React o React.js es una libreria de JavaScript para creacion de interfaces de usuario desarrollada por meta.
Utiliza una sintaxis basada en componentes que te permite desarrollar de forma eficiente interfaces de usuario ya sean simples o complejas.
## Instalar React
Existen diferentes formas de instalar y crear proyectos en React, por muchos años se utilizaba Create-react-app pero una herramienta que ha ganado mucha popularidad es Vite.
Vite es una herramienta que permite crear un proyecto de React en un par de minutos e instalar todas sus dependencias.
Para instalar React con Vite puedes hacerlo con npm o yarn.
### Guia
#### Debemos tener previamente instalado npm
##### Para crear un proyecto en react, en la terminal escribir el siguiente comando:
- npm create vite@latest
##### Luego instalamos las dependencias, en la terminal escribir el siguiente comando:
- npm install
##### Luego arrancamos el servidor, en la terminal escribir el siguiente comando:
- npm run dev
##### Para instalar tailwind como dependencia de desarrollo, en la terminal escribir el siguiente comando:
- npm install -D tailwindcss postcss autoprefixer
##### Luego para crear los archivos, en la terminal escribir el siguiente comando:
- npx tailwindcss init -p
##### Para subir nuestro proyecto a Netlify, en la terminal escribir el siguiente comando, para que se cree una carpeta llamada dist.
- npm run build
## Que es JSX en React
- JSX es una sintaxis que permite combinar JS y HTML.
- Todos los elementos HTML se pueden utilizar.
- No todas las funciones de JS se pueden utilizar.
## Que son los componentes en React
- Los componentes te van a permitir dividir tu codigo en partes reutilizables.
- Los componentes utilizan la extension .js o .jsx y se importan con un import de JavaScript.
- Se puede pasar informacion de un componente a otro por Props.
## Que es state en React
- El state es la fuente de la verdad (source of truth) de tu app.
- Un listado de clientes, un carrito de compras lleno o vacio, un usuario autenticado es lo que determina cual es el estado o state de tu app.
- Para definir state en React, se importa useState y la funcion al momento de utilizarse nos retorna 2 valores: state y la funcion que modifica el state.
## Administrar state en React
- useState es suficiente para crear aplicaciones en React.
- El state no debe modificarse directamente; para eso se debe utilizar la funcion que lo modifica.
- En un equipo de trabajo o un proyecto grande se recomienda administrar el state con un state global como Context, Zustand, Recoil o Redux.
## Evento en React
- Todas las aplicaciones requieren eventos: cuando un usuario escribe en un campo, realiza un submit a un formulario, click en un elemento.
- Los eventos en React inician con la palabra on seguido del evento en Mayuscula; onClick, onSubmit, onChange, son algunos ejemplos.
- Estos eventos se agregan via atributo en el HTML.
## useEffect en React
- useEffect es un hook que se ejecuta una vez que el componente esta listo, y toma un array de dependencias.
- En su listado de dependencias se le puede pasar un state para "escuchar" los cambios que ocurren en ese state; en caso de que el state se actualice, useEffect se va a ejecutar nuevamente.
- useEffect puede ser complejo al inicio; pero una vez que lo domines, crear proyectos en React sera mas sencillo.
