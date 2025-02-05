useFetchApi - Custom React Hook para Solicitudes API
useFetchApi es un custom hook de React diseñado para simplificar y optimizar el proceso de realizar solicitudes HTTP en tus aplicaciones de React. Proporciona una interfaz limpia y reutilizable para realizar solicitudes GET, POST, PUT y DELETE, manejando estados de carga, errores y la gestión de datos de respuesta.

Características
Llamadas API Simples: Realiza fácilmente solicitudes GET, POST, PUT y DELETE con un código mínimo.

Gestión del Estado de Carga: Automáticamente rastrea el estado de carga de las solicitudes, permitiéndote mostrar indicadores de carga o deshabilitar botones durante las llamadas API.

Manejo de Errores: Captura y muestra errores de solicitudes fallidas, facilitando la visualización de mensajes de error para los usuarios.

Métodos Reutilizables: Proporciona métodos reutilizables (get, post, put, del) para operaciones HTTP comunes, reduciendo el código repetitivo.

Cabeceras y Credenciales Personalizables: Soporta cabeceras personalizadas y credenciales (por ejemplo, para autenticación) en cada solicitud.

Seguridad de Tipos: Desarrollado con TypeScript, asegurando la seguridad de tipos y una mejor experiencia para el desarrollador.
Métodos Disponibles
get(url, headers, credentials): Realiza una solicitud GET.

post(url, body, headers, credentials): Realiza una solicitud POST con un cuerpo.

put(url, body, headers, credentials): Realiza una solicitud PUT con un cuerpo.

del(url, headers, credentials): Realiza una solicitud DELETE.

Valores Retornados
data: Los datos de respuesta de la llamada API.

loading: Un booleano que indica si una solicitud está en progreso.

error: Un mensaje de error si la solicitud falla.

get, post, put, del: Funciones para realizar las respectivas solicitudes HTTP.

Personalización
Puedes personalizar el comportamiento de useFetchApi modificando la función fetchRequest o extendiendo el hook para soportar características adicionales como caché, reintentos o cancelación de solicitudes.

Contribuciones
¡Las contribuciones son bienvenidas! Si tienes sugerencias, reportes de errores o solicitudes de características, por favor abre un issue o envía un pull request.
