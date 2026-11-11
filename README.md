PROYECTO PAG WEB ROPA 
URL DEL REPOSITORIO:GENEKRISTI/portafolio_ecommerce_ropa   

URL DE GITHUB PAGES: https://genekristi.github.io/portafolio_ecommerce_ropa/ 

URL DE VERCEL: portafolioecommerceropa.vercel.app 
 
Tipo de Proyecto: Aplicación Web SPA (Single Page Application) & E-Commerce de Moda Vintage 
1. Introducción y Visión del Proyecto 
En este documento presento el desarrollo completo de Atelier Genesis 1920s, una tienda virtual diseñada bajo una estética Art Déco / Vintage de los años 20. Mi objetivo principal fue crear una experiencia de compra elegante, sofisticada y funcional, combinando tonos clásicos (ébano, verde oscuro, dorado y crema) con una arquitectura web moderna que permite explorar un catálogo de alta costura, gestionar una bolsa de compras persistente y generar tickets térmicos en PDF de forma automática. 
2. Stack Tecnológico Utilizado 
Para construir esta plataforma desde cero, seleccioné e integré las siguientes tecnologías frontend: 
•	HTML5 Semántico: Utilicé etiquetas estructurales (header, nav, main, footer) para organizar el contenido de manera limpia y accesible. 
•	CSS3 Vanilla: Diseñé una hoja de estilos personalizada con variables CSS, tipografías clásicas (Cinzel y Playfair Display), efecto Glassmorphism en la barra de navegación y animaciones suaves en las tarjetas de productos. 
•	JavaScript (ES6+): Programé toda la lógica interactiva, incluyendo el filtrado por categorías, el buscador en tiempo real, el manejo del carrito con LocalStorage y la generación dinámica de documentos. 
•	Bootstrap 5.3.3: Lo implementé para garantizar un diseño 100% responsivo en computadoras, tabletas y teléfonos móviles, además de utilizar sus modales interactivos. 
•	FontAwesome 6.5.1: Integré iconografía elegante para los botones de acción, el carrito flotante y mis enlaces a redes sociales. 
•	SweetAlert2 & html2pdf.js: Usé SweetAlert2 para mostrar notificaciones visuales amigables y html2pdf.js para convertir el resumen de compra en un ticket térmico descargable de 80 mm. 
 
3. Estructura del Proyecto en Visual Studio Code 
Para mantener el código ordenado y fácil de mantener, organicé mi espacio de trabajo en Visual Studio Code de forma modular: 
Plaintext 
AtelierGenesis_1920s/ 
│ 
├── index.html          # Estructura principal, modales y footer personalizado 
├── styles.css          # Paleta Art Déco, tipografía y diseño responsivo 
├── script.js           # Catálogo curado, carrito en LocalStorage y ticket PDF 
├── genesis caba.jpg    # Fotografía de perfil para el pie de página 
└── README.md           # Presentación técnica del repositorio 
4. Funcionalidades Clave Implementadas 
•	Catálogo Dinámico y Buscador en Tiempo Real: Los usuarios pueden filtrar las prendas por categoría (Todo, Vestidos, Sastrería, Accesorios) o escribir directamente en el buscador para encontrar una pieza al instante. 
•	Vista Detallada en Modal: Al hacer clic en "Ver más", se abre una ventana modal con la imagen ampliada, descripción, precio y selector de cantidad. 
•	Bolsa de Compras Persistente (LocalStorage): El carrito guarda los productos seleccionados en el navegador, permitiendo eliminar artículos o vaciar la bolsa sin perder los datos al recargar la página. 
•	Pasarela de Pago y Ticket Térmico PDF: Al confirmar el pago, el sistema cierra los modales de forma segura, maqueta un recibo limpio en formato de 80 mm con fuente monoespaciada y lo descarga automáticamente como ticket_atelier_genesis.pdf. 
•	Footer Personalizado: En el pie de página incluí mi fotografía de perfil, mi nombre (GENESIS CABA), una breve descripción profesional y mis enlaces directos a Facebook, Instagram y YouTube. 


<img width="783" height="440" alt="image" src="https://github.com/user-attachments/assets/64531e7f-cde0-47aa-a975-943b6812c6cf" />
<img width="779" height="438" alt="image" src="https://github.com/user-attachments/assets/3382206b-ee1f-4e85-8173-a5e1d3025845" />
<img width="574" height="323" alt="image" src="https://github.com/user-attachments/assets/06a593ba-eac3-4c47-a969-35c3119408fc" />




6. Respaldo en GitHub y Despliegue en Vercel (Método Visual) 
A. Subida a GitHub 
1.	Ingresé a mi cuenta en GitHub y creé un nuevo repositorio público llamado 
atelier-genesis-1920s. 
2.	Seleccioné la opción "uploading an existing file" para subir los archivos de forma visual sin usar consola. 
3.	Arrastré y solté mis archivos (index.html, styles.css, script.js, README.md y genesis caba.jpg) dentro del área de carga. 
4.	Escribí el mensaje de confirmación y presioné "Commit changes" para guardar el proyecto en la nube. 
B. Publicación en Vercel 
1.	Inicié sesión en Vercel vinculando directamente mi cuenta de GitHub. 
2.	En el panel principal, hice clic en "Add New... > Project" e importé el repositorio atelier-genesis-1920s. 
3.	Dejé la configuración estática predeterminada y presioné "Deploy". 
4.	En pocos segundos, Vercel generó la URL pública con certificado SSL (HTTPS) lista para compartir y visualizar desde cualquier dispositivo



<img width="886" height="498" alt="image" src="https://github.com/user-attachments/assets/c0fcaab5-99a7-4c94-9615-0577a5e6b315" />

<img width="831" height="467" alt="image" src="https://github.com/user-attachments/assets/7e85c894-a4c4-4180-a0a3-23d959bcda0f" />

<img width="779" height="443" alt="image" src="https://github.com/user-attachments/assets/c1c1c326-d2f7-4abf-bed9-9a1cd82c53f8" />



<img width="369" height="292" alt="image" src="https://github.com/user-attachments/assets/436c0e80-f20a-44d6-9b25-b5f342bca823" />



 
