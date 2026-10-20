# Portfolio de Andrés Alvear

Portfolio de proyectos de Andrés Alvear, ingeniero electrónico (M.Sc., Universidad de Chile) con más de diez años entre procesamiento de señales en FPGA, verificación de chips y desarrollo de software de alto rendimiento en Go y Python.

[LinkedIn](https://www.linkedin.com/in/andres-alvear-028bb01ba/) · [GitHub](https://github.com/andriu5)

## Qué hay en el portfolio

### Casos de proyecto

Tres proyectos documentados en detalle: desafío, cómo llegué a la solución, mi contribución, resultados y aprendizajes.

| Caso | Periodo | En una línea |
| --- | --- | --- |
| [Espectrómetro digital del radiotelescopio MINI](caso-mini.html) | 2015–2016 · U. de Chile | Back-end en FPGA que separa las bandas laterales de un receptor de 80–116 GHz: más de 40 dB de rechazo, el doble de ancho de banda y primera luz en la nebulosa de Orión. |
| [Validación automática de Formality ECO](caso-fmeco.html) | 2023–2026 · Synopsys | Validación de cada nightly build con ETL en Python, una granja HPC y un agente de IA; la revisión de cada ciclo pasó de un día a minutos. |
| [DegradIA: predicción de corrosión](caso-degradia.html) | 2025 · U. de Antofagasta | Plataforma en Go y Python que simula la corrosión del acero en sales fundidas, validada contra SEM-EDS (R² = 0,97), en uso en el CDEA y origen de Novatherm Analytics. |

### Radio SDR desde Santiago

[Guías paso a paso](radio/index.html) de mi estación RTL-SDR: instalación, barridos de la banda FM con `rtl_power`, grabación y decodificación de satélites meteorológicos Meteor, mapa de canales de TV digital ISDB-Tb y grabaciones IQ para testbench de FPGA.

### Otros proyectos

- **Data Science:** análisis exploratorio ([EDA Pima Indians](https://github.com/andriu5/EDA-pima-indians)) y un [sistema de recomendación musical](https://github.com/andriu5/music-recommendation-system).
- **[Near-Earth Objects](https://github.com/andriu5/NEOs):** herramienta de línea de comandos para consultar datos de asteroides cercanos a la Tierra.
- **[Meme Generator](https://github.com/andriu5/Meme_Generator):** app en Flask y CLI que genera memes.
- **[Photodiode data logger](https://github.com/andriu5/photodiode_project):** detector de cuadrante para alinear haces láser.
- **[File Importer](https://github.com/andriu5/StrategyObject_FileImporter):** prototipo del patrón Strategy en Python 3.10.

## Estructura del repositorio

```
index.html            Portada con todos los proyectos
caso-*.html           Casos de proyecto
radio/                Guías de la estación RTL-SDR (sitio aparte, sin JavaScript)
images/               Imágenes y diagramas de los proyectos
assets/               CSS, JS y fuentes de la plantilla Massively
elements.html,        Páginas de referencia de la plantilla original
generic.html
```

## Verlo en local

Es un sitio estático, sin build. Desde la raíz del repositorio:

```bash
python -m http.server 8000
```

y abre <http://localhost:8000>.

## Créditos

- **Diseño:** [Massively](https://html5up.net/massively) de [HTML5 UP](https://html5up.net) (AJ, [@ajlkn](https://twitter.com/ajlkn)), con licencia [Creative Commons Attribution 3.0](https://html5up.net/license). La plantilla original fue modificada: contenido propio, páginas nuevas y ajustes menores de estilo.
- **Íconos:** [Font Awesome](https://fontawesome.com).
- **Scripts:** [jQuery](https://jquery.com), [Scrollex](https://github.com/ajlkn/jquery.scrollex) y [Responsive Tools](https://github.com/ajlkn/responsive-tools).
- **Foto de la tarjeta NEOs:** NASA en [Unsplash](https://unsplash.com).

## Licencia

La plantilla Massively se distribuye bajo CC BY 3.0. Los textos, casos de proyecto, diagramas y fotos propias son © Andrés Alvear. El detalle está en [LICENSE.txt](LICENSE.txt).
