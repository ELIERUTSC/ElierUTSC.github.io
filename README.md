# ElierUTSC.github.io
Se enfocara en desarrollo WEB profesional


Estructura básica del documento
html
<!DOCTYPE html>
Indica que el documento usa HTML5.

html
<html lang="es">
Comienza el documento HTML.

lang="es" especifica que el idioma principal es español.

🧠 <head>: Metadatos y configuración
html
<meta charset="UTF-8">
Define la codificación de caracteres como UTF-8 (soporta acentos, símbolos, etc.).

html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
Hace que el diseño sea responsivo en dispositivos móviles.

html
<title>...</title>
Define el título que aparece en la pestaña del navegador.

html
<script src="https://cdn.tailwindcss.com"></script>
Carga Tailwind CSS desde un CDN para usar clases utilitarias de diseño.

🎨 <body>: Contenido visible
html
<body class="bg-gray-100 font-sans leading-relaxed">
bg-gray-100: fondo gris claro.

font-sans: fuente sin serifas.

leading-relaxed: espaciado entre líneas relajado.

📦 Contenedor principal
html
<div class="max-w-3xl mx-auto bg-white shadow-lg rounded-2xl p-8 mt-10">
max-w-3xl: ancho máximo moderado.

mx-auto: centrado horizontal.

bg-white: fondo blanco.

shadow-lg: sombra grande.

rounded-2xl: bordes redondeados.

p-8: padding interno.

mt-10: margen superior.

🧍 Encabezado
html
<div class="text-center">
Centra el contenido horizontalmente.

html
<h1 class="text-3xl font-bold mt-4 text-gray-800">
text-3xl: texto grande.

font-bold: negrita.

mt-4: margen superior.

text-gray-800: color gris oscuro.

html
<p class="text-gray-600">
Texto en gris medio.

🔗 Sección de contacto
html
<div class="flex justify-center gap-6 mt-6">
flex: usa Flexbox.

justify-center: centra los elementos.

gap-6: espacio entre ellos.

mt-6: margen superior.

html
<img class="w-10 h-10 hover:scale-110 transition-transform">
Imagen de 40x40 px.

hover:scale-110: se agranda al pasar el cursor.

transition-transform: suaviza la animación.

📄 Secciones de contenido
Cada sección (<section>) sigue un patrón:

html
<h2 class="text-2xl font-semibold text-orange-600 border-b-2 border-orange-300 pb-2">
text-2xl: subtítulo grande.

font-semibold: seminegrita.

text-orange-600: color naranja intenso.

border-b-2: borde inferior.

border-orange-300: color del borde.

pb-2: padding inferior.

html
<p class="mt-2 text-gray-700 text-justify">
mt-2: margen superior.

text-gray-700: texto gris oscuro.

text-justify: texto justificado.

✅ Lista de habilidades
html
<div class="grid grid-cols-2 gap-4 mt-2 text-gray-700">
grid grid-cols-2: dos columnas.

gap-4: espacio entre elementos.

mt-2: margen superior.

text-gray-700: color del texto.
