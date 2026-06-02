# Guitar 🎸

Aplicación desarrollada con React y TypeScript que permite explorar un catálogo de guitarras, agregar productos al carrito de compras y visualizar el resumen de la compra en tiempo real.

## Características

* Visualización de un catálogo de guitarras.
* Agregar productos al carrito de compras.
* Incrementar la cantidad de productos seleccionados.
* Mostrar precio individual de cada guitarra.
* Calcular el total a pagar automáticamente.
* Persistencia de datos utilizando Local Storage.
* Gestión de estado mediante Hooks de React.
* Implementación de un Hook personalizado para reutilizar lógica relacionada con el carrito de compras.

## Tecnologías utilizadas

* React
* TypeScript
* Vite

## Conceptos aplicados

Durante el desarrollo de este proyecto se trabajaron conceptos fundamentales de React y TypeScript:

* `useState` para la gestión del estado local.
* `useEffect` para sincronizar información con Local Storage.
* Custom Hooks para encapsular lógica reutilizable.
* Props para la comunicación entre componentes.
* Tipado estático con TypeScript.
* Manipulación de arreglos y renderizado dinámico de componentes.
* Persistencia de datos en el navegador mediante Local Storage.

## Funcionalidades del carrito

El carrito de compras permite:

* Agregar guitarras desde el catálogo.
* Evitar la pérdida de información al recargar la página.
* Mostrar la cantidad de cada producto agregado.
* Calcular el subtotal de cada producto.
* Calcular el total de la compra.
* Vaciar el carrito cuando el usuario lo desee.

## Objetivo del proyecto

Este proyecto fue desarrollado como práctica para fortalecer conocimientos en React y TypeScript, aplicando el manejo de estado, persistencia de datos y reutilización de lógica mediante Hooks personalizados en un caso de uso real: un carrito de compras para un catálogo de guitarras.

## Se crearon dos ramas, una con el custom Hook y la otra con useReducer
