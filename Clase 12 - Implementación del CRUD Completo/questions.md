Clase 12 - React
Comenzado el	viernes, 14 de noviembre de 2025, 12:53
Estado	Finalizado
Finalizado en	viernes, 14 de noviembre de 2025, 12:59
Tiempo empleado	5 minutos 47 segundos
Puntos	10,00/11,00
Calificación	9,09 de 10,00 (90,91%)
Pregunta 1
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué propiedad se utiliza en el formulario para vincular los campos con el estado?
Pregunta 1Respuesta

a.
initialValue

b.
defaultValue

c.
value 

d.
placeholder
Retroalimentación
En React, la propiedad value se utiliza para vincular el estado con el valor de los campos del formulario, lo que convierte al formulario en controlado.

La respuesta correcta es: value 
Pregunta 2
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué hace la función agregarProducto en el ProductsContext?
Pregunta 2Respuesta

a.
El estado global se limpia completamente.

b.
El nuevo producto se añade al estado global de productos. 

c.
El producto se envía a MockAPI automáticamente.

d.
El producto se elimina de la lista.
Retroalimentación
La función agregarProducto añade un nuevo producto al estado global de productos, lo que actualiza la lista de productos.

La respuesta correcta es: El nuevo producto se añade al estado global de productos. 
Pregunta 3
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Cuál es la función de Context API en este proyecto de gestión de productos?
Pregunta 3Respuesta

a.
Asegurar que los productos siempre estén sincronizados con la API.

b.
Validar los datos del formulario.

c.
Proveer una forma de manejar el estado global de los productos y sus operaciones.

d.
Crear rutas protegidas para usuarios autenticados.
Retroalimentación
Context API se utiliza para manejar el estado global de los productos, facilitando su edición y eliminación en toda la aplicación.

La respuesta correcta es: Proveer una forma de manejar el estado global de los productos y sus operaciones.
Pregunta 4
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué debe hacer un formulario controlado en React?
Pregunta 4Respuesta

a.
Permitir múltiples envíos del formulario sin restricciones.

b.
Evitar la validación de los datos del formulario.

c.
Mantener los datos del formulario sincronizados con el estado del componente.

d.
Controlar únicamente los campos de texto.
Retroalimentación
En un formulario controlado, los datos del formulario están siempre sincronizados con el estado del componente.

La respuesta correcta es: Mantener los datos del formulario sincronizados con el estado del componente.
Pregunta 5
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué sucede si el formulario no pasa las validaciones en handleSubmit?
Pregunta 5Respuesta

a.
El formulario se envía y los errores se muestran en la consola.

b.
El formulario se limpia y el usuario recibe un mensaje de error.

c.
Los errores se almacenan en el estado y se muestran en pantalla junto a los campos correspondientes.

d.
La página se recarga automáticamente para corregir los errores.
Retroalimentación
Si los datos no son válidos, los errores se almacenan en el estado y se muestran al usuario junto a los campos correspondientes.

La respuesta correcta es: Los errores se almacenan en el estado y se muestran en pantalla junto a los campos correspondientes.
Pregunta 6
Incorrecta
Se puntúa 0,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Cuál es el propósito de la validación en el formulario de edición de productos?
Pregunta 6Respuesta

a.
Garantizar que todos los campos del formulario sean obligatorios y que el precio sea mayor a 0.

b.
Validar si el producto existe en la base de datos.

c.
Permitir que el producto se agregue aunque falten datos.

d.
Validar que el nombre del producto tenga al menos 5 caracteres.
Retroalimentación
Repasá los contenidos correspondientes

La respuesta correcta es: Garantizar que todos los campos del formulario sean obligatorios y que el precio sea mayor a 0.
Pregunta 7
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué sucede si el precio ingresado en el formulario es menor o igual a 0?
Pregunta 7Respuesta

a.
No se muestra ningún mensaje de error.

b.
El formulario se envía sin problemas.

c.
Se muestra un mensaje de error indicando que el precio debe ser mayor a 0.

d.
El formulario se limpia automáticamente.
Retroalimentación
La validación del precio asegura que sea mayor a 0. Si no es así, se muestra un mensaje de error junto al campo correspondiente.

La respuesta correcta es: Se muestra un mensaje de error indicando que el precio debe ser mayor a 0.
Pregunta 8
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué sucede cuando el usuario confirma la eliminación de un producto?
Pregunta 8Respuesta

a.
El producto se actualiza en la base de datos.

b.
Se redirige al usuario a otra página.

c.
El producto se oculta, pero no se elimina.

d.
Se realiza una solicitud DELETE a la API para eliminar el producto.
Retroalimentación
La eliminación se realiza a través de una solicitud DELETE a MockAPI solo si el usuario confirma la acción.

La respuesta correcta es: Se realiza una solicitud DELETE a la API para eliminar el producto.
Pregunta 9
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué debe hacer el ProductsContext en la clase?
Pregunta 9Respuesta

a.
Gestionar el estado global de los productos en la aplicación. 

b.
Establecer las validaciones del formulario.

c.
Crear las rutas de la aplicación para productos.

d.
Conectar el formulario de agregar productos con MockAPI.
Retroalimentación
El ProductsContext se utiliza para gestionar el estado global de los productos, permitiendo que los componentes accedan y actualicen el estado sin pasar props manualmente.

La respuesta correcta es: Gestionar el estado global de los productos en la aplicación. 
Pregunta 10
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué debe hacer un formulario controlado en React?
Pregunta 10Respuesta

a.
Mantener los datos del formulario sincronizados con el estado del componente.

b.
Controlar únicamente los campos de texto.

c.
Evitar la validación de los datos del formulario.

d.
Permitir múltiples envíos del formulario sin restricciones.
Retroalimentación
En un formulario controlado, los datos del formulario están siempre sincronizados con el estado del componente.

La respuesta correcta es: Mantener los datos del formulario sincronizados con el estado del componente.
Pregunta 11
Correcta
Se puntúa 1,00 sobre 1,00
Marcar pregunta
Enunciado de la pregunta
¿Qué función tiene el hook useEffect al obtener los productos desde MockAPI?
Pregunta 11Respuesta

a.
Realizar la validación de los datos del producto.

b.
Inicializar el estado con datos de un archivo local.

c.
Ejecutar una solicitud a la API para obtener los productos al cargar el componente.

d.
Permitir que los productos se actualicen en tiempo real.
Retroalimentación
useEffect se utiliza para ejecutar la solicitud a la API al cargar el componente y así obtener los productos.

La respuesta correcta es: Ejecutar una solicitud a la API para obtener los productos al cargar el componente.