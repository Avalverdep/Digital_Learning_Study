Tecnología: ¿evolución o involución?

Redes sociales, IA y comprensión lectora de los jóvenes europeos Proyecto EDA del Data Science Bootcamp de The Bridge (Bilbao, 2026) · Andoni

La lectura de los alumnos de 15 años lleva años cayendo en Europa. La media de 15 países de la UE fue estable de 2000 a 2018 y desde entonces ha perdido 30 puntos en PISA. Este proyecto analiza si esa caída se relaciona con el uso problemático de las redes sociales y qué papel puede jugar la inteligencia artificial.

Hipótesis y resultados
Hipótesis	Resultado
1. Los países con más uso problemático de redes obtienen peores resultados de lectura en PISA	Sí, con fuerza moderada (r entre −0,40 y −0,58). Con un giro: los países con menos uso son los que más caen
2. La caída empezó antes de la pandemia y coincide con el scroll infinito y el vídeo corto	A medias: la caída fuerte llega después de 2018 y sigue en 2025, pero se solapa con la pandemia
3. La IA ayuda o perjudica según cómo se use	Sí, según los estudios: la IA que da la respuesta empeora el examen (−17 %); la IA tutor no perjudica

Conclusión: no es la pantalla, es el uso.

Datos
PISA (OCDE): lectura y matemáticas por país, 2000–2025 (Our World in Data y resultados de PISA 2025).
HBSC 2022: % de jóvenes de 15 años con uso problemático de redes sociales (Lisbon Council).
Eurostat 2025: jóvenes de 16 a 24 años que usan IA generativa (Our World in Data).
Estudios sobre aprendizaje: Roediger y Karpicke (2006) y Bastani et al. (2025, PNAS).
Introducción: Google Trends (Animal Crossing) y movilidad de Google durante la pandemia.

Las fuentes completas están en la memoria.

Tecnologías
Análisis: Python, pandas, NumPy, Jupyter.
Visualización: matplotlib, seaborn y Plotly (mapa interactivo).
Presentación: reveal.js, HTML, CSS y JavaScript con GSAP.
Estructura
├── README.md
├── memoria.pdf          # memoria del proyecto
├── EDA_Andoni.ipynb     # notebook con todo el análisis
├── data/                # datasets utilizados
└── presentacion/        # presentación en reveal.js
    ├── index.html
    ├── css/
    ├── js/
    ├── img/             # gráficas exportadas desde el notebook
    └── graficas/        # mapa interactivo (Plotly)
