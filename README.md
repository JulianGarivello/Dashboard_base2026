Dashboard de Diseño 2026 - Protela

Este es un tablero de control interactivo desarrollado para la visualización y gestión de la carga de trabajo del equipo de diseño. Permite procesar bases de datos en formato Excel para generar indicadores automáticos sobre trabajos pendientes por diseñador y el estado de las muestras en las diferentes tecnologías de impresión.

!

 Características

Visualización de Carga: Gráfica de barras dinámica que ordena a los diseñadores por volumen de trabajos pendientes.

Seguimiento de Muestras: Resumen en tiempo real de muestras en proceso para tecnología Digital (Reggiani, Atexco, Mimaki) y Convencional.

Procesamiento Local: Los datos se procesan directamente en el navegador del usuario utilizando SheetJS, garantizando privacidad y rapidez.

Interfaz Moderna: Diseño basado en Glassmorphism con fondo animado de estrellas, optimizado para una experiencia visual "Premium".

Responsive: Totalmente compatible con dispositivos móviles, tablets y computadoras de escritorio.

Tecnologías Utilizadas

HTML5/CSS3: Estructura y estilos base.

Tailwind CSS: Framework de utilidades para un diseño rápido y responsivo.

JavaScript (ES6+): Lógica de negocio y manipulación del DOM.

Chart.js: Para la generación de gráficas interactivas.

SheetJS (XLSX): Para la lectura y parseo de archivos Excel.

Requisitos del Archivo Excel

Para que el dashboard procese los datos correctamente, el archivo Excel debe cumplir con lo siguiente:

Nombre de la Hoja: Preferiblemente llamada 2026. Si no existe, el sistema tomará la primera hoja disponible.

Columnas Requeridas:

DISEÑADOR: Nombre del responsable.

TECNOLOGÍA o TECNOLOGIA: Tipo de impresión (DIGITAL o CONVENCIONAL).

MÁQUINA o MAQUINA: Nombre de la máquina (REGGIANI, ATEXCO, MIMAKI).

FECHA_ENTREGA: Si está vacío, el sistema lo cuenta como pendiente.

FECHA_TRABAJO: Indica que el trabajo ha iniciado.

FECHA_ENTREGA_MUESTRA: Si está vacío y tiene fecha de trabajo, se cuenta como "En Proceso".

Instalación y Uso

Clona este repositorio o descarga el archivo dashboard_diseñadores.html.

Asegúrate de tener los logos de la empresa en la misma carpeta:

NuevologoProtela1.png copia.png (Versión blanca recomendada).

NuevologoProtela1.png.webp (Versión de respaldo).

Abre el archivo dashboard_diseñadores.html en cualquier navegador web moderno.

Haz clic en "Cargar Archivo Excel" y selecciona tu base de datos de diseño.

Personalización

El diseño utiliza clases de Tailwind CSS. Si deseas cambiar los colores de la gráfica o la intensidad del brillo, puedes modificar las variables en la función actualizarUI dentro de las etiquetas <script>.

Desarrollado para el equipo de Diseño de Protela - 2026.
