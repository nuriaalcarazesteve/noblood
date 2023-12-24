# No Blood - Página Web

## Descripción
"No Blood" es una página web ficticia que presenta contenido relacionado con películas de género de terror y suspense. La página está diseñada para ofrecer información sobre películas, incluidos detalles como pósters, títulos y una interfaz de paginación simple.

## Características
- **Navegación:** La página cuenta con una barra de navegación que te permite explorar diferentes categorías, como Terror, Sangre y Psicológico.
- **Contenido Dinámico:** Las películas populares se cargan dinámicamente desde la API de The Movie Database (TMDb) con funcionalidad de paginación.
- **Diseño Responsivo:** La página está diseñada para ser compatible con dispositivos de diferentes tamaños, desde teléfonos móviles hasta computadoras de escritorio.

## Tecnologías Utilizadas
- HTML
- CSS
- JavaScript (Fetch API para acceder a la API de TMDb)

## Instrucciones de Uso
1. Clona este repositorio en tu máquina local.
   ```bash
   git clone https://github.com/tu-usuario/no-blood-page.git

   Configuración del Proyecto
El archivo appterror.js contiene el código JavaScript para manejar la paginación y cargar películas desde la API de TMDb.
Los estilos se gestionan en el archivo estilospaginas.css.
Código - Explicación Básica
appterror.js
  
  Paginación y Carga de Películas:
Las variables pagina, btnAnterior, y btnSiguiente gestionan la paginación.
La función cargarPeliculas utiliza la Fetch API para obtener datos de películas desde la API de TMDb.
El código maneja las respuestas de la API y actualiza dinámicamente el contenido de la página.
estilospaginas.css
  
  Estilos:
Contiene reglas CSS para dar formato y diseño a la página.
Se establecen estilos para la barra de navegación, contenedores, imágenes y texto.
Recursos Externos

The Movie Database (TMDb): https://www.themoviedb.org/
