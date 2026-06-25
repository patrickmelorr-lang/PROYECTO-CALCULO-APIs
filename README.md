#  Proyecto de Cálculo - Aplicación de APIs en Tiempo Real

## Objetivo General

Demostrar, mediante el análisis de datos obtenidos en **tiempo real** a través de **APIs de fácil acceso**, 
la existencia de una **relación lineal con pendiente positiva** entre dos variables en distintos ámbitos:
- Ingeniería de software
- Tecnología / LLMs
- Finanzas / Criptomonedas
- Artes / Música
- Procesamiento de datos

Aplicando técnicas de **regresión lineal** que permiten calcular la recta que mejor se ajusta a los datos: **y = ax + b**

---

##  Integrantes y APIs Asignadas

| Integrante | API | Variable X | Variable Y | Notebook |
|-----------|-----|-----------|-----------|----------|
| Melo Ramos Patrick J. | GitHub | Nº Repositorios | RAM Consumida (MB) | `notebooks/01_API_GitHub.ipynb` |
| Integrante 2 | OpenAI/Anthropic | Tokens Input | Tiempo Respuesta (ms) | `notebooks/02_API_LLM.ipynb` |
| Integrante 3 | CoinGecko | Días Transcurridos | Precio BTC (USD) | `notebooks/03_API_Bitcoin.ipynb` |
| Integrante 4 | Spotify/LastFM | Nº Canciones | Duración Total (min) | `notebooks/04_API_Spotify.ipynb` |
| Integrante 5 | COCOMO | KLOC | Esfuerzo (meses-hombre) | `notebooks/05_COCOMO.ipynb` |

---

##  Estructura del Proyecto
````
PROYECTO-CALCULO-APIs/
├── README.md                    (este archivo)
├── requirements.txt             (dependencias Python)
├── .gitignore                  (archivos ignorados)
│
├── notebooks/                   (notebooks individuales de cada integrante)
│   ├── 01_API_GitHub.ipynb
│   ├── 02_API_LLM.ipynb
│   ├── 03_API_Bitcoin.ipynb
│   ├── 04_API_Spotify.ipynb
│   └── 05_COCOMO.ipynb
│
├── assets/
│   ├── images/                  (gráficas PNG y SVG)
│   └── outputs/                 (archivos JSON con datos)
│
├── utils/
│   └── shared_functions.py      (funciones reutilizables)
│
└── docs/
    ├── INSTRUCCIONES_INTEGRANTES.md
    └── PRESENTACION_GRUPAL.md
````

