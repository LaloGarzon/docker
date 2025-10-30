# Microservicios con Docker 

## Tecnologías Utilizadas
- **ASP.NET Core**
- **Entity Framework Core**
- **SQL Server**
- **Docker**
- **Docker Compose**

## Patrón de Arquitectura
El proyecto sigue una arquitectura de microservicios, donde cada servicio (por ejemplo, `ProductService`, `OrderService`) es independiente y se comunica con otros a través de APIs. Se utiliza Docker para la contenedorización de cada servicio, lo que facilita su despliegue y escalabilidad.

## Archivos del Proyecto
- `Dockerfile`: Define cómo construir la imagen de Docker para cada servicio.
- `docker-compose.yml`: Orquesta múltiples contenedores Docker, incluyendo los microservicios y la base de datos.
- `Program.cs`: Punto de entrada del proyecto ASP.NET Core y Configuración del pipeline de la aplicación y servicios
