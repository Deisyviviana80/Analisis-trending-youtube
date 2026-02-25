# 📊 Análisis Exploratorio de Datos: YouTube Trending

Análisis exploratorio de videos en tendencia en YouTube para 5 regiones del mundo, entre noviembre de 2017 y junio de 2018.

---

## 📁 Estructura del proyecto

```
analisis-trending-youtube/
│
├── trending_by_time.csv          # Dataset original
├── youtube_trending_analisis.ipynb  # Limpieza, análisis y visualizaciones
└── README.md
```

---

## 📌 Descripción

Este proyecto analiza el comportamiento de los videos en tendencia (*trending*) en YouTube durante 8 meses, estudiando cómo varía el volumen de contenido viral según la región, la categoría y el tiempo.

El notebook integra desde la carga y limpieza del dataset hasta el análisis exploratorio completo con visualizaciones y conclusiones, todo en un flujo continuo y documentado.

---

## 🌍 Regiones analizadas

| País | Código |
|------|--------|
| Francia | FR |
| India | IN |
| Japón | JP |
| Rusia | RU |
| Estados Unidos | US |

---

## 🎬 Categorías incluidas

18 categorías de contenido, entre ellas: `Entertainment`, `Music`, `News & Politics`, `People & Blogs`, `Comedy`, `Gaming`, `Sports`, `Science & Technology`, entre otras.

---

## 📒 Contenido del notebook

El archivo `youtube_trending_analisis.ipynb` está organizado en 10 secciones:

1. **Descripción del proyecto**
2. **Carga e inspección inicial** de los datos
3. **Limpieza y preprocesamiento** — conversión de fechas, espacios en blanco, duplicados
4. **Resumen estadístico general**
5. **Categorías dominantes** a nivel global
6. **Comparación entre regiones** con gráfico de barras y torta
7. **Evolución temporal** mes a mes por región
8. **Heatmap** de volumen absoluto y distribución relativa por categoría y región
9. **Top 5 categorías** por cada región
10. **Distribución estadística** de `videos_count` y **conclusiones**

---

## 💡 Principales hallazgos

- **Entertainment** domina el Trending global con el 27,9% del total, más del doble que cualquier otra categoría.
- Cuatro regiones (EE.UU., Francia, Rusia e India) presentan volúmenes muy similares; **Japón** queda notablemente por debajo.
- **Diciembre 2017** fue el mes de mayor actividad para la mayoría de regiones, mostrando un claro efecto estacional de fin de año.
- **Rusia** es el único mercado donde *People & Blogs* supera a Entertainment, reflejando una fuerte cultura de creadores de contenido personal.
- La distribución de `videos_count` es asimétrica (sesgo de 2.33), con mediana en 18 videos y picos de hasta 220 en eventos excepcionales.

---

## 🛠️ Tecnologías utilizadas

- Python 3.11
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/analisis-trending-youtube.git
```

2. Instala las dependencias:
```bash
pip install pandas matplotlib seaborn jupyter
```

3. Abre el notebook:
```bash
jupyter notebook youtube_trending_analisis.ipynb
```

---

## 📂 Fuente de los datos

Dataset de YouTube Trending disponible públicamente. Contiene registros de videos en tendencia por región, fecha y categoría entre noviembre 2017 y junio 2018.

---

## 👤 Autor

Hecho por **DEisy Hurtado**  
www.linkedin.com/in/deisyhurtado-analistadedatos
