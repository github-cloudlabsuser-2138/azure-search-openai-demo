# Backend Application

## Descripción

Esta es la aplicación backend de nuestro proyecto. Proporciona la lógica del lado del servidor, la gestión de datos y las API necesarias para interactuar con el frontend y otros servicios.

## Estructura del Proyecto

El directorio `backend` contiene los siguientes componentes principales:

- **Controladores**: Gestionan las solicitudes entrantes y devuelven las respuestas adecuadas.
- **Modelos**: Definen la estructura de los datos y las interacciones con la base de datos.
- **Servicios**: Contienen la lógica de negocio principal.
- **Configuración**: Archivos de configuración para el entorno de desarrollo y producción.

## Requisitos Previos

Asegúrate de tener instalados los siguientes requisitos antes de ejecutar la aplicación:

- Python 3.8 o superior
- [Poetry](https://python-poetry.org/) para la gestión de dependencias
- Base de datos compatible (por ejemplo, PostgreSQL, MySQL, SQLite)

## Instalación

1. Clona el repositorio:

   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd app/backend
   ```

2. Instala las dependencias:

   ```bash
   poetry install
   ```

3. Configura las variables de entorno necesarias. Puedes usar un archivo `.env` para definirlas.

## Ejecución

Para iniciar el servidor backend, ejecuta el siguiente comando:

```bash
poetry run python main.py
```

El servidor estará disponible en `http://localhost:8000` por defecto.

## Pruebas

Ejecuta las pruebas unitarias con el siguiente comando:

```bash
poetry run pytest
```

## Contribución

Si deseas contribuir al desarrollo del backend, consulta el archivo [CONTRIBUTING.md](../../CONTRIBUTING.md) para obtener más detalles.

## Licencia

Este proyecto está licenciado bajo los términos del archivo [LICENSE](../../LICENSE).