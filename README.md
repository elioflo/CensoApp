# TP5 Front+Back

### Introducción
A pesar de la pandemia, se ha decidido llevar a cabo el censo 2021 en Argentina.
Para ello, se solicita realizar una aplicación web que sea capaz de gestionar la información obtenida de cada persona. Dichos datos son:
```
Tipo y número de documento (obligatorio).
Nombre y apellido (obligatorio).
Fecha de nacimiento (obligatorio).
Sexo (obligatorio).
Dirección.
Teléfono.
Ocupación.
Ingreso económico mensual (obligatorio).
```
### Requerimientos
Los datos deberán ser almacenados en una base de datos y la aplicación debe permitir hacer el alta, baja, modificación y consulta de personas censadas. Queda a criterio del desarrollador qué modelo de base de datos utilizar y qué tipo de datos.
Luego de cada operación, el usuario de la aplicación debe obtener una respuesta que le permita saber si el proceso ha salido bien o no. El redireccionamiento de páginas es una opción.

Con fines estadísticos, nuestro programa debe ser capaz de crear un reporte (exportar a uno o varios archivos) con la siguiente información:
- Lista de todas las personas, mostrando toda su información, ordenadas de forma ascendente según su apellido.
- Lista de todas las personas mayores de 18 años que están desocupadas.
- Lista de todas las personas que están por debajo de la línea de pobreza. Se considera pobre a una persona cuyos ingresos son inferiores a cinco mil pesos mensuales.
- Cantidad de mujeres y cantidad de hombres entre la población.

La aplicación debe tener una interfaz web (frontend) y debe ser capaz de conectarse a través de servlets con el servidor (backend).

Tengan en cuenta que es deseable el uso de las tecnologías de frontend que vimos en clase o que están en el temario (Lit Element o React).
