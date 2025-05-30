🌐 Características del Proyecto

✅ Frontend
    Uso de HTML para estructurar las distintas páginas del sistema.
    Estilos definidos mediante CSS personalizados para una presentación visual coherente.
    Incorpora JavaScript para mostrar el menú de navegación.
    Arquitectura basada en páginas estáticas.

🛠️ Backend
    El backend está realizado en PHP, con scripts que manejan funcionalidades CRUD como edición y eliminación de registros.
    En lugar de usar una base de datos tradicional (MySQL, SQLite, etc.), el sistema utiliza un archivo JSON para almacenar datos.

🗂️ Almacenamiento de Datos
    Se almacena la información en un archivo json.
    Esta aproximación simplifica la implementación y despliegue al no depender de un motor de bases de datos.

⚙️ Requisitos y Recomendaciones para la Ejecución
    Para ejecutar correctamente este proyecto en un entorno local, ten en cuenta lo siguiente:
    Servidor local requerido:
        Dado que el backend usa PHP, es necesario ejecutarlo en un entorno de servidor como:
            XAMPP
            Laragon
            WampServer
    Ubicación del proyecto:
        Coloca la carpeta del proyecto dentro del directorio correspondiente de tu servidor local, por ejemplo:
            En XAMPP: htdocs/Practica1_DevOps
            En Laragon: www/Practica1_DevOps
    Acceso al proyecto:
        Luego de configurar el servidor, accede desde el navegador:
        http://localhost/Practica1_DevOps/pages/index.html
    Uso de Live Server (VS Code):
        Solo útil para previsualizar los archivos HTML y CSS. No servirá para ejecutar el backend PHP. Usa servidor local como se indicó antes.
