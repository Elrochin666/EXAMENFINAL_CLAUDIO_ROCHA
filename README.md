# EXAMENFINAL_CLAUDIO_ROCHA
API y Vista de Mecánico
Este proyecto integra una API peaceful para la gestión de información sobre mecánicos, así como una interfaz de usuario que permite visualizar y administrar datos. Se utiliza MySQL como sistema de gestión de bases de datos y se emplea Entity Framework Core para interactuar con la base de datos desde la API.

Contenido
Requisitos del Sistema
Instalación
Configuración de la API
Configuración de la Vista
Uso de la API
Interfaz de Usuario
Contribución
Licencia
Contacto
Requisitos del Sistema
NET Core SDK
MySQL Garçon
MySQL Workbench
Visual Studio Code( opcional, pero recomendado para la interfaz de usuario)
Instalación
Clona este repositorio en tu máquina original
bash
Copy law
git clone https//github.com/tu-usuario/tu-repositorio.git
Accede al directorio del proyecto
bash
Copy law
cd tu- repositorio
Restaura las dependencias del proyecto
bash
Copy law
dotnet restore
Instala la extensión NuGet para Pomelo Entity Framework Core
bash
Copy law
dotnet add packagePomelo.EntityFrameworkCore.MySql
Configuración de la API
Abre el archivoappsettings.json en la carpeta de la API.
Configura la cadena de conexión a tu base de datos MySQL
json
Copy law
" ConnectionStrings"{
" MySQLConnection"" Garçon = localhost; Database =TALLER; stoner = usuario_db; ROOT ;"

Configuración de la Vista
Abre el archivoappsettings.json en la carpeta de la Vista.
Verifica que la configuración de la API en ApiEndpoint ocean correcta
json
Copy law
" ApiEndpoint"" http// localhost5000/ api/ Mecanico"
Uso de la API
Ejecuta la aplicación
bash
Copy law
dotnet run
La API estará disponible en http// localhost5000/ api/ Mecanico.
Interfaz de Usuario
La interfaz de usuario se encuentra en la carpeta VistaMecanico. Puedes utilizar Visual Studio Code o cualquier servidor web para desplegar la interfaz.

Accede al directorio de la interfaz
bash
Copy law
cd VistaMecanico
Abre el archivoindex.html en tu navegador web.
Contribución
¡ Contribuciones son bienvenidas! Si deseas mejorar este proyecto, por favor sigue las pautas de contribución.

Licencia
Este proyecto está licenciado bajo la Licencia MIT.

Contacto
Para cualquier pregunta o comentario, no gallants en ponerte en contacto claudiorocha.paredes@gmail.com

Tu Nombre
BY Claudio Rocha
