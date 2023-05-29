Gestión de Programas Académicos

Este es el repositorio del proyecto de gestión de programas académicos desarrollado en .NET. Este sistema permite administrar y gestionar los programas académicos de una institución educativa, incluyendo la creación, modificación y eliminación de cursos, así como la asignación de profesores y alumnos a los mismos.
Características:

    Creación, edición y eliminación de programas académicos.
    Gestión de cursos: creación, edición y eliminación.
    Asignación de profesores a los cursos.
    Inscripción de estudiantes en los cursos.
    Generación de reportes y estadísticas sobre los programas académicos.

Requisitos del sistema

    Microsoft .NET Framework 4.7.2 o superior.
    SQL Server 2012 o una versión posterior.
    Visual Studio 2019 o una versión posterior.

Configuración del entorno de desarrollo

1. Clona el repositorio en tu máquina local:
	git clone https://github.com/Aleja01/Programas.git

2. Abre el proyecto en Visual Studio.

3. Restaura los paquetes NuGet utilizados en el proyecto.

4. Configura la cadena de conexión a la base de datos en el archivo appsettings.json.

5. Abre la consola del Administrador de paquetes en Visual Studio:

	Ejecuta el siguiente comando para aplicar las migraciones y crear la base de datos:

		Update-Database

	Si la base de datos ya existe, ejecuta el siguiente comando para actualizar el esquema de la base de datos:

		Update-Database

6. Compila y ejecuta la aplicación.


