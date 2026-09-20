Solucion de Ejercicios en Python
Estructuras de Datos y Funciones

Este repositorio contiene las soluciones en Python para tres sistemas utilizando estructuras de datos anidadas organizadas de forma modular.

--------------------------------------------------

Ejercicio 1: Sistema de Red Social

Descripcion
Modelado de un perfil de usuario que contiene datos personales, listas de amigos y publicaciones utilizando diccionarios y listas anidadas.

Funcionalidades
- Permite agregar nuevas publicaciones al perfil.
- Modifica datos de ubicacion del usuario.
- Permite eliminar elementos especificos de la lista de amigos.

Casos de Prueba
- Entrada: Modificar ciudad a Madrid, agregar post con 5 likes, eliminar segundo amigo.
- Salida esperada:
  - Ciudad actualizada a Madrid.
  - Lista de amigos actualizada con 2 elementos.
  - Lista de publicaciones incrementada a 2 elementos.

--------------------------------------------------

Ejercicio 2: Sistema de Tienda Online
Descripcion
Estructura de gestion comercial que administra inventario de productos, registro de clientes y pedidos con sus estados correspondientes.

Funcionalidades
- Incorporacion de nuevos productos al inventario.
- Actualizacion dinamica del estado de los pedidos.
- Busqueda y filtrado de pedidos asociados a la cuenta de correo de un cliente.

Casos de Prueba
- Entrada: Nuevo producto Pantalon ($39.99, stock 75), cambiar pedido 101 a Entregado, consultar por maria@example.com.
- Salida esperada:
  - Inclusion del nuevo item en la lista de productos.
  - Pedido 101 reflejando el estado Entregado.
  - Impresion del pedido correspondiente a Maria.

--------------------------------------------------
Ejercicio 3: Sistema de Gestion Universitaria

Descripcion
Modelo academico para controlar estudiantes, asignaturas registradas, calificaciones y el personal docente.

Funcionalidades
- Registro de nuevos alumnos en asignaturas activas.
- Funcion de calculo del promedio acumulado de calificaciones por estudiante.
- Consulta de nomina de estudiantes matriculados por codigo de curso.

Casos de Prueba
- Entrada: Agregar estudiante Pedro Martinez al curso CS101, calcular promedio de Laura Gomez (notas: 4.5, 4.0, 5.0).
- Salida esperada:
  - Promedio calculated: 4.50
  - Lista de inscritos en CS101: Laura Gomez y Pedro Martinez.
