# Red de Interpretaciones Musicales / Musical Performance Network 

**A pedagogical tool for the analysis and visualization of musical interpretations of the same work.**

---

## English

### Overview

**Interpretation Network** is an interactive visualization tool designed for musicians, researchers, students and educators to explore how a single musical work evolves through different performances. 
The tool generates a dynamic graph that connects a central "Original Score" node to various interpretations sourced from YouTube. By adding metadata such as year and region, users can transform the network into a **Spatio-Temporal Map** to visualize the work's historical and geographic journey.

This tool is particularly useful for analyzing:
* Comparative performance studies
* Historical evolution of interpretive styles
* Geographic distribution of musical versions
* Pedagogical tracking of repertoire

### Features

* **Dynamic Graph Generation:** Automatically builds visual networks from YouTube links.
* **Spatio-Temporal Mapping:** Organizes versions in a radial diagram based on recording year and region.
* **Analysis Sheets:** Input specific metadata (performer, year, location, and extra material links).
* **Timeline Slider:** Filter nodes to observe the work's evolution across decades.
* **Zero-Backend Portability:** Projects are stored and shared entirely through the URL.
* **Browser-based:** Runs 100% with no installation required.

### How It Works

The tool uses a central reference node (the score). When YouTube links are added:
1. **Metadata Retrieval:** The tool fetches titles automatically.
2. **Relational Mapping:** Each version is linked to the core work.
3. **Radial Positioning:** When "Spatio-Temporal View" is active, the recording year determines the distance from the center (radius) and the region determines the angle.
4. **Data Encoding:** Every change updates the browser's URL, allowing for instant sharing.

### Installation / Usage

[**Access the live tool here**](https://evagarciafmusic.github.io/red-interpretaciones/)

1. Click the central node to set the work's details.
2. Paste YouTube links in the left panel and click **"Generate Graph"**.
3. Edit each node to add performer data and geographic region.
4. Use the **Time Slider** and **Spatio-Temporal View** to analyze the results.

### License

This project is licensed under the **MIT License**. Feel free to modify, reuse, and adapt it for educational or research purposes. See the [LICENSE](LICENSE) file for details.

---

## Español

### Descripción general

**Red de Interpretaciones Musicales** es una herramienta interactiva de visualización diseñada para que músicos, investigadores, estudiantes y docentes exploren cómo una misma obra musical se transforma a través de sus diversas ejecuciones.
La herramienta genera un grafo dinámico que vincula un nodo central ("Partitura Original") con distintas interpretaciones de YouTube. Al cargar metadatos de año y región, los usuarios pueden transformar la red en un **Mapa Crono-Geográfico** para visualizar el recorrido histórico y geográfico de la obra.

Es especialmente útil para analizar:
* Estudios comparativos de interpretación
* Evolución histórica de estilos interpretativos
* Distribución geográfica de versiones musicales
* Seguimiento pedagógico de repertorio

### Características

* **Generación dinámica de grafos:** Crea redes visuales a partir de enlaces de YouTube de forma automática.
* **Visión Crono-Geográfica:** Organiza las versiones en un diagrama radial según el año de grabación y la región.
* **Fichas de Análisis:** Carga metadatos específicos (intérprete, año, lugar y enlaces a material extra).
* **Slider de Tiempo:** Filtra nodos para observar la evolución de la obra a través de las décadas.
* **Privacidad y Portabilidad:** Los proyectos se guardan y comparten íntegramente a través de la URL.
* **Sin instalación:** Funciona 100% en el navegador.

### Cómo funciona

La herramienta utiliza un nodo central de referencia. Cuando se agregan links de YouTube:
1. **Extracción de Metadatos:** El título se recupera automáticamente.
2. **Mapeo Relacional:** Cada versión se vincula a la obra base.
3. **Posicionamiento Radial:** En la "Visión Crono-Geográfica", el año determina la distancia al centro (radio) y la región determina el ángulo.
4. **Codificación de Datos:** Cada cambio actualiza la URL del navegador, permitiendo compartir el trabajo al instante.

### Instalación / Uso

[**Acceder a la herramienta aquí**](https://evagarciafmusic.github.io/red-interpretaciones/)

1. Hacé clic en el nodo central para configurar los datos de la obra.
2. Pegá los enlaces de YouTube en el panel izquierdo y presioná **"Generar Grafo"**.
3. Editá cada nodo para agregar los datos del intérprete y la región geográfica.
4. Utilizá el **Slider de tiempo** y la **Visión Crono-Geográfica** para analizar los resultados.

### Licencia

Este proyecto está bajo la **Licencia MIT**. Podés modificar, reutilizar y adaptar el código libremente para fines educativos o de investigación. Consultá el archivo [LICENSE](LICENSE) para más detalles.

---
*Note/Nota: This project uses the URL to store information. / Este proyecto utiliza la URL para almacenar la información.*
