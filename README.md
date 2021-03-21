# Proyecto-Final-2021
Proyecto web en el que se desarrollará un modelo de negocio orientado a una empresa de viajes interplanetarios.
El modelo de negocios consta de las siguientes partes :
 - Clientes
 - Administradores
 - Soporte Técnico
 - Publicación (hilo)
 - Vuelos
 - Naves
 - Escalas

En la base de datos se contemplarán los elementos anteriormente listados y otros no mostrados, después de realizar las adaptaciones extrictamente necesarias para su creación se añadirán datos a la misma.

La aplicación Web ha de contemplar la siguiente operativa :
- Index Inicio de sesión con opción de registrarse a través de un formulario
- Debe ofrecer al usuario con rol user una vista que contenga los siguientes apartados:
  - Mostrar carta estelar (Vista con todos los destinos, vuelos, escalas, ect...)
  - Ver perfil en el mismo se mostrará toda la información relevante como:
    - Visualizar vuelos o transbordos comprados con toda la información relevante de los mismos
    - Visualizar hilos abiertos con referencia de los vuelos o transbordos sobre los que se han abierto
    - Cancelar pedido
 - Cerrar sesión
- Debe ofrecer al usuario con rol admin una vista que contenga los siguientes apartados:
 - Visualizar todos los usuarios registrados y su información
 - Visualizar todos los vuelos
 - Administrador de vuelos donde el usuario podra añadir, borrar o modificar los vuelos que existen en ese momento en la base de datos
 - Cerrar sesión
- Debe ofrecer al usuario con rol support una vista que contenga los siguientes apartados:
 - Visualización de todos los hilos abiertos por los diferentes usuarios de la página
 - Posibilidad de gestionar los hilos pudiendo responderlos o eleminarlos según se estime oportuno
 - Cerrar sesión
Cabe aclarar que, cada usuario con rol user podrá añadir una reseña así como abrir un hilo en sus diferntes vuelos o transbordos realizados o por realizar
pudiendo así informar de un problema o notificar de un error en la web.
