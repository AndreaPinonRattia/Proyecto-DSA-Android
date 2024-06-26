# Android de UPZ-APOCALYPSE

En este proyecto hemos creado un juego que funciona tanto en una interfaz web como en una aplicación Android gestionado mediante una REST API. Además, puede funcionar en un entorno de producción local y almacena los datos a través de una base de datos de MariaDB (HeidiSQL), que contiene tres tablas: User, Inventory e Item.

Implementaciones específicas: Shared preferences, SplashScreen y Spinner.

Operaciones:

GET 
- Obtener lista de usuarios.
- Obtener lista de objetos en la tienda.
- Obtener inventario de un usuario.
- Obtener lista de denuncias.
- Obtener lista de consultas.
- Obtener lista de preguntas frecuentes (FAQs).

POST
- Registrar un nuevo usuario.
- Iniciar sesión con credenciales.
- Eliminar usuario con credenciales.
- Realizar una consulta sobre la app.
  
PUT 
- Comprar objeto.
- Cancelar compra de objeto.
- Actualizar usuario.
- Enviar una denuncia.
