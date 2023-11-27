[x] Aplicar DAO
[x] Aplicar DTO
[x] Aplicar Controllers
[x] Aplicar patron Repository
[x] Modificar /current usando DTO que tiene que generar una capa de abstraccion para ocultar campos sensibles
[x] Aplicar sistema de politicas. Debe permitir contar con un sistema de validacion para roles (revisar ppt)
[x] Crear modelo Ticket // REVISAR EL PURCHASE_DATE_TIME
[x] Implementar en carts la ruta /:cid/purchase
[] Usar servicio Tickets para poder generar un ticket con los datos de compra
[x] Generar modulo de mocking para el servidor. Al inicializarse generar 100 productos con el mismo formato que la peticion de Mongo. Debe ocurrir en /mockingproducts
[] Customizador de errores y crear un diccionario para errores mas comunes al crear un producto, agregarlo al carrito, etc
[x] Definir sist de niveles por prioridad (debug, http, info, warning, error, fatal)
[x] Implementar logger para desa y para prod, el de desar loggea a partir del nivel debug, SOLO EN CONSOLA. El de prod solo a partir de nivel info
[x] Enviar en un transporte de archivos a partir del nivel de error en un "errors.log"
[] Agregar logs de valor alto en puntos importantes del servidor(errores, advertencias, etc) y que se muestren a partir de WINSTON(buscar)
[x] Endpoint /loggerTest que permita probar todos los logs
