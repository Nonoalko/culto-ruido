[README.txt](https://github.com/user-attachments/files/34595967/README.txt)
CULTO RUIDO — primera web

PUBLICAR EN GITHUB PAGES
1. En GitHub crea un repositorio nuevo llamado: culto-ruido
2. Déjalo en Public (público) y crea el repositorio.
3. Sube index.html y la carpeta images.
4. En el repositorio entra a Settings > Pages.
5. En "Build and deployment", elige "Deploy from a branch".
6. Selecciona la rama main y la carpeta / (root), guarda.
7. Espera un momento y GitHub mostrará la dirección de tu web.

AÑADIR IMÁGENES
1. Abre la carpeta images de este proyecto.
2. Coloca ahí tus imágenes JPG, PNG o WEBP.
3. Usa nombres sencillos, por ejemplo: figura-01.jpg
4. En index.html busca el arreglo `const products = [...]`.
5. Añade un objeto siguiendo este ejemplo:

{ name: "Mi escultura", category: "Objetos 3D", type: "Bajo pedido",
  price: "Consultar", image: "images/mi-escultura.jpg",
  description: "Escultura impresa en 3D" },

IMPORTANTE
- Las categorías válidas son: Objetos 3D, Ropa, Prints y Digital.
- Para cambiar el correo de contacto, busca `hola@cultoruido.com` en index.html.
- Esta versión es un catálogo visual funcional: búsqueda y filtros funcionan.
- Todavía no cobra ni procesa pedidos. Más adelante añadiremos un botón de pedido por WhatsApp o un carrito.
- No subas datos privados ni contraseñas al repositorio.
