Prerrequisitos
Sistema Operativo: Este manual es específico para Windows.
Acceso de Administrador: Necesitas permisos de administrador en tu máquina.
Instalación de MongoDB
Descarga:

Visita MongoDB Download Center y descarga el instalador para Windows.
Ejecución del Instalador:

Ejecuta el archivo descargado (.msi).
Selecciona "Complete" para una instalación completa.
Marca la opción "Install MongoDB as a Service" para que MongoDB se ejecute automáticamente como un servicio en Windows.
Finalizar Instalación:

Completa el asistente de instalación. MongoDB se instalará en tu sistema y se configurará para ejecutarse como un servicio.
Configuración de MongoDB
Verificar la Instalación:

Abre "Panel de control" > "Herramientas administrativas" > "Servicios".
Busca el servicio "MongoDB" y asegúrate de que esté en estado "En ejecución".
MongoDB Compass:

Descarga e instala MongoDB Compass, una herramienta GUI para gestionar MongoDB.
Una vez instalado, ábrelo y conéctate al servidor MongoDB local usando la URI mongodb://localhost:27017.
Importación de Datos desde JSON
Preparar Archivos JSON:

Asegúrate de que tus archivos JSON estén en el formato correcto y accesibles, por ejemplo, en el directorio C:\data\json.
Usar MongoDB Compass:

Abre MongoDB Compass.
Conéctate a tu base de datos usando mongodb://localhost:27017.
Selecciona o crea una nueva base de datos en la sección "Databases".
Importar Colección:

Dentro de tu base de datos, selecciona o crea una nueva colección.
Haz clic en el botón "Add Data" y selecciona "Import File".
Navega hasta el archivo JSON en C:\data\json y selecciónalo.
Asegúrate de que el formato seleccionado sea "JSON" y luego haz clic en "Import".