# Generador de Pictogramas

![Generador de Pictogramas](httpshttps://via.placeholder.com/700x300.png?text=Generador+de+Pictogramas)

Un sistema web simple y completo para generar pictogramas interactivos. Creado con HTML, CSS y JavaScript puro, este proyecto se enfoca en la simplicidad, accesibilidad y facilidad de uso.

**Enlace al sitio en vivo:** [https://mjmc4498.github.io/GeneradorDePictogramas/](https://mjmc4498.github.io/GeneradorDePictogramas/)

## ✨ Características

*   **Búsqueda Unificada:** Busca pictogramas en múltiples librerías (ARASAAC, OpenMoji) de forma simultánea.
*   **Generación Interactiva:** Combina un pictograma con un texto personalizado para crear una imagen compuesta.
*   **Descarga Múltiple:** Descarga el pictograma generado como imagen PNG o como documento PDF.
*   **Historial Persistente:** Guarda un historial de tus últimas creaciones para reutilizarlas fácilmente (usando `localStorage`).
*   **Diseño Responsivo:** Interfaz limpia y adaptable a cualquier tamaño de pantalla, desde móviles hasta escritorios.
*   **Cero Dependencias de Backend:** Funciona completamente en el navegador, sin necesidad de un servidor.
*   **Arquitectura Escalable:** Código modular y bien estructurado, listo para futuras expansiones.

## 🚀 Instalación y Uso

Este proyecto no requiere un proceso de instalación complejo. Puedes usarlo de dos maneras:

### 1. Uso Local

1.  **Clona el repositorio:**
    ```bash
    git clone https://github.com/mjmc4498/GeneradorDePictogramas.git
    ```
2.  **Navega a la carpeta del proyecto:**
    ```bash
    cd GeneradorDePictogramas
    ```
3.  **Abre el archivo `index.html`:**
    Haz doble clic en el archivo `index.html` o arrástralo a tu navegador web preferido (Chrome, Firefox, etc.). ¡Y eso es todo!

### 2. Despliegue en GitHub Pages

GitHub Pages te permite alojar sitios web estáticos de forma gratuita directamente desde tu repositorio.

1.  **Ve a la configuración de tu repositorio:**
    En la página principal de tu repositorio, haz clic en la pestaña "Settings".
2.  **Navega a la sección "Pages":**
    En el menú de la izquierda, haz clic en "Pages".
3.  **Configura la fuente de despliegue:**
    *   En la sección "Build and deployment", bajo "Source", selecciona "Deploy from a branch".
    *   Asegúrate de que la rama seleccionada sea `main` (o la rama principal que estés usando) y la carpeta sea `/ (root)`.
    *   Haz clic en "Save".
4.  **Espera la confirmación:**
    GitHub tardará unos minutos en construir y desplegar tu sitio. Una vez que esté listo, verás un mensaje verde en la parte superior de la sección "Pages" con la URL de tu sitio.

## 📖 Manual del Sistema

El uso de la aplicación es muy intuitivo y sigue un flujo de trabajo guiado:

1.  **Busca un Pictograma:**
    *   En la sección "1. Busca un Pictograma", escribe una palabra clave (ej: "casa", "correr", "feliz") en el campo de búsqueda.
    *   Haz clic en el botón "Buscar" o presiona "Enter".
    *   La galería de resultados se llenará con pictogramas de las librerías ARASAAC y OpenMoji. La fuente de cada pictograma se indica en la esquina inferior derecha de la imagen.
2.  **Selecciona un Pictograma:**
    *   Haz clic en el pictograma que desees usar. Verás que se resalta con un borde azul y aparece en el área de "Previsualización".
3.  **Añade un Texto:**
    *   En la sección "2. Añade un Texto", escribe la frase corta que acompañará a tu pictograma.
    *   El texto aparecerá automáticamente debajo del pictograma en la previsualización.
4.  **Descarga tu Creación:**
    *   Una vez que hayas seleccionado un pictograma y añadido un texto, los botones de descarga se activarán.
    *   Haz clic en "Descargar PNG" para guardar el pictograma como un archivo de imagen.
    *   Haz clic en "Descargar PDF" para guardarlo como un documento PDF.
5.  **Reutiliza desde el Historial:**
    *   En la parte inferior de la página, encontrarás la sección "Historial Reciente".
    *   Cada vez que descargues un pictograma, se guardará aquí.
    *   Haz clic en cualquier pictograma del historial para cargarlo instantáneamente en la previsualización y reutilizarlo.

---

Creado con ❤️ por [mjmc4498](https://github.com/mjmc4498).
