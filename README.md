Sistema de Gestión de Calidad del Agua en Costa Rica

📌 Descripción General

Este sistema permite a los responsables de acueductos en Costa Rica reportar la calidad del agua potable, utilizando herramientas de ArcGIS Online. Consta de dos plataformas principales:

Sitio Web General (Público): Para operadores de acueductos y otros entes regulados, proporcionando acceso a información y reportes.

Sitio Web para el Ministerio de Salud (Intranet Privada): Para el personal autorizado del MS, que gestiona la validación de inscripciones y revisa los reportes.

El sistema aprovecha ArcGIS Online y sus herramientas, incluyendo Survey123, ArcGIS Experience Builder, ArcGIS Dashboard y ArcGIS Hub, para la gestión de datos y su visualización.

🚀 Infraestructura

Este sistema está completamente alojado en ArcGIS Online, utilizando:

Survey123 y Survey123 Connect: Formularios interactivos para la captura de datos.

ArcGIS Dashboard: Visualización y análisis en tiempo real de los reportes.

ArcGIS Hub: Portal de acceso para usuarios externos y publicación de datos.

ArcGIS Experience Builder: Desarrollo de las interfaces web.

🏗️ Módulos del Sistema

1️⃣ Sistema de Inscripción de Usuarios

Permite el registro de responsables técnicos de acueductos. El proceso incluye:

Ingreso del usuario en el sistema.

Inscripción mediante un formulario validado por el MS.

Validación y autenticación con código enviado por correo electrónico.

2️⃣ Sistema de Reporte Semestral de Calidad de Agua

Módulo en el que los responsables técnicos envían reportes cada seis meses. Características:

Generación de reportes con información detallada.

Identificación con un código único para trazabilidad.

Notificación automática por correo tras el envío del reporte.

3️⃣ Sistema de Revisión y Monitoreo de Reportes

Herramienta exclusiva del MS para analizar los informes recibidos:

Revisión y validación de datos.

Emisión de Orden Sanitaria en caso de irregularidades.

Generación de Oficio de Conformidad si el reporte cumple los estándares.

4️⃣ Sistema de Alerta Temprana y Comunicación

Permite la divulgación pública de la información sobre la calidad del agua:

Tablero Público con datos accesibles para la ciudadanía.

Tablero Histórico de Reportes para consulta y análisis de información pasada.

🛠️ Instalación y Configuración

1️⃣ Clonar el repositorio:

 git clone https://github.com/usuario/calidad-agua-cr.git

2️⃣ Acceder al directorio:

 cd calidad-agua-cr

3️⃣ Revisar la documentación y estructura de archivos.

📝 Documentación y Archivos Clave

📂 Estructura del repositorio:
/calidad-agua-cr
│── /docs                     # Documentación del sistema
│── /survey123                # Formularios XLSForm de Survey123
│── /dashboard                # Configuración exportada del ArcGIS Dashboard
│── /hub                      # Configuraciones de ArcGIS Hub
│── /scripts                  # Scripts en Python/JS para automatización
│── /config                   # Archivos JSON de configuraciones
│── /tests                    # Pruebas del sistema
│── .gitignore                # Para ignorar archivos innecesarios
│── README.md                 # Guía de instalación y configuración
│── LICENSE                   # Licencia del código
│── CHANGELOG.md              # Registro de cambios en cada versión

📧 Contacto y Soporte

Si tienes preguntas o necesitas soporte, contacta a jerc315@gmail.com
