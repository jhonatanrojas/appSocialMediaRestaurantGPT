#Proyecto PHP con MVC y SOLID

Este proyecto utiliza el patrón de diseño MVC (Modelo-Vista-Controlador), principios SOLID y DDD (Domain-Driven Design) para estructurar el código de manera limpia y mantenible. Utiliza el paquete `nikic/fast-route` para el manejo de rutas y `php-di/php-di` para la inyección de dependencias.

es proyecto ligero que te permite escalar cualquier aplicacion

## Descripción de los directorios

- `assets`: Contiene los archivos estáticos como CSS, JavaScript e imágenes.
- `config`: Contiene archivos de configuración, como `services.php` para la configuración de la inyección de dependencias.
- `controllers`: Contiene los controladores de la aplicación, que manejan la lógica de la interfaz de usuario.
- `core`: Contiene clases fundamentales como `Controller`, `Core`, `Database` y `Model`.
- `helpers`: Contiene funciones auxiliares que se pueden utilizar en toda la aplicación.
- `models`: Contiene los modelos de la aplicación, que representan las entidades de negocio y contienen la lógica de negocio.
- `repositories`: Contiene los repositorios, que proporcionan una abstracción para el acceso a los datos.
- `services`: Contiene los servicios, que encapsulan la lógica de negocio que no pertenece a ninguna entidad específica.
- `views`: Contiene las vistas de la aplicación, que son responsables de presentar la información al usuario- `uploads`: Contiene los archivos subidos por los usuarios.
- `vendor`: Contiene las dependencias de Composer.

## Dependencias

- `nikic/fast-route`: Un paquete de enrutamiento rápido y simple para PHP. Se utiliza para manejar todas las rutas de la aplicación.
- `php-di/php-di`: Un contenedor de inyección de dependencias para PHP. Se utiliza para gestionar las dependencias de la aplicación y hacer que el código sea más flexible y fácil de probar.

## Cómo ejecutar el proyecto

1. Clona el repositorio en tu máquina local.
2. Navega al directorio del proyecto en tu terminal.
3. Ejecuta `composer install` para instalar las dependencias del proyecto.
4. Configura tu entorno y la base de datos en `config.php` y `environment.php`.
5. Ejecuta el servidor de desarrollo de PHP con `php -S localhost:8000` (o cualquier puerto de tu elección).
6. Abre tu navegador y navega a `http://localhost:8000` para ver la aplicación en acción.

## Contribuir

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request si tienes algo que añadir o cambiar.

## Licencia

Este proyecto está licenciado bajo los términos de la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

@jhonatanrojas