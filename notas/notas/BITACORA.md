# Bitacora de JavaScript interactivo
 
Laboratorio 08: JavaScript Interactivo - DOM, Eventos y Objetos.
Navegador usado: (escribe aqui cual usaste)
 
## Ejercicio 2: Seleccionar y modificar el DOM
 | Instruccion | Que cambio en la pantalla | Se mantiene al recargar (Si/No) |
|-------------|---------------------------|---------------------------------|
| textContent desde la consola |Cambió el título |No |
| textContent desde app.js |Cambió el título a "Hola TECSUP" |SI |
| style.color |El título cambió a color azul |SI |
| classList.add |El párrafo del mensaje cambió a fondo amarillo |SI |
| createElement + appendChild |Se agregó "JavaScript" como un nuevo elemento a la lista |SI |

## Ejercicio 3: Evento click
 | Tipo de evento | Que accion lo dispara | Cuanto suma por accion |
|----------------|-----------------------|------------------------|
| click |Hacer un clic normal sobre el botón |Suma 1 |
| dblclick |Hacer doble clic rápido sobre el botón |Suma 1 |
| mouseover |Pasar el cursor del mouse por encima del botón (sin hacer clic) |Suma 1 (cada vez que entras al botón) |

## Ejercicio 4: Eventos input y submit
 | Prueba | Que paso en la pantalla | Se recargo la pagina (Si/No) |
|--------|-------------------------|------------------------------|
| Escribir en el campo nombre |El texto del saludo cambia letra por letra en tiempo real |No |
| Enviar sin preventDefault |El texto "Enviado" aparece solo un instante y desaparece rápido |Si |
| Enviar con preventDefault, correo sin @ |Muestra el mensaje "Correo no valido: falta @" en letras rojas |No |
| Enviar con preventDefault, correo con @ |Muestra el mensaje "Enviado: [tu correo]" en la pantalla de forma permanente |No |

## Ejercicio 5: Clases y objetos
 | Objeto | nombre | precio | descripcion() | conDescuento(0.25) |
|--------|--------|--------|---------------|--------------------|
| laptop |Laptop |2500 |Laptop - S/ 2500.00 |1875 |
| mouse |mouse |45 |Mouse - S/ 45.00 |33.75 |
| teclado |teclado |120 |Teclado - S/ 120.00 |90 |
| monitor |monitor |680 |Monitor - S/ 680.00 |510 |
Permite automatizar y reutilizar el código de forma eficiente. Si necesitas agregar 100 productos nuevos, solo debes registrarlos en un arreglo de JavaScript sin tocar el HTML, evitando repetir código manualmente y reduciendo errores.

## Ejercicio 6: DOM, eventos y objetos juntos
| Prueba | Total que muestra la pagina | Correcto (Si/No) |
|--------|-----------------------------|------------------|
| Cuaderno 12.50 |12.50 |SI |
| + Lapicero 3.20 |15.70 |SI |
| + Mochila 89.90 |105.60 |SI |
| Sin Number() |No cambia |NO |

--------------------------------------------------------------
 
| Pieza | Linea de tu codigo donde aparece | Para que sirve |
|-------|----------------------------------|----------------|
| DOM |document.querySelector / createElement |Modificar la interfaz visual de la página web. |
| Evento |formProducto.addEventListener("submit", ...) |Detectar y reaccionar a las acciones del usuario |
| Objeto |new Carrito() / new Producto(...) |Guardar los datos y manejar la lógica en JavaScript |
