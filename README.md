# 📊 Análisis Exploratorio de Datos: YouTube Trending

Análisis exploratorio de videos en tendencia en YouTube para 5 regiones del mundo, entre noviembre de 2017 y junio de 2018.

---

## 📁 Estructura del proyecto

```
analisis-trending-youtube/
│
├── trending_by_time.csv        # Dataset original
├── procesamiento.ipynb         # Limpieza y preprocesamiento de datos
├── eda_trending_completo.ipynb # Análisis exploratorio completo con visualizaciones
└── README.md
```

---

## 📌 Descripción

Este proyecto analiza el comportamiento de los videos en tendencia (*trending*) en YouTube durante 8 meses, estudiando cómo varía el volumen de contenido viral según la región, la categoría y el tiempo.

Se trabaja sobre el dataset `trending_by_time.csv`, que registra para cada combinación de **región**, **fecha** y **categoría** el número de videos que lograron posicionarse en la sección Trending de YouTube.

---

## 🌍 Regiones analizadas

| País | Registros |
|------|-----------|
| Francia | ~2.400 |
| India | ~2.400 |
| Japón | ~2.400 |
| Rusia | ~2.400 |
| Estados Unidos | ~2.400 |

---

## 🎬 Categorías incluidas

18 categorías de contenido, entre ellas: `Entertainment`, `Music`, `News & Politics`, `People & Blogs`, `Comedy`, `Gaming`, `Sports`, `Science & Technology`, entre otras.

---

## 🔍 Contenido del análisis

El notebook `eda_trending_completo.ipynb` incluye:

1. **Resumen estadístico general** del dataset
2. **Categorías dominantes** a nivel global
3. **Comparación entre regiones** con gráfico de barras y torta
4. **Evolución temporal** mes a mes por región
5. **Heatmap** de volumen absoluto y distribución relativa por categoría y región
6. **Top 5 categorías** por cada región
7. **Distribución estadística** de la variable `videos_count`
8. **Conclusiones y próximos pasos**

---

## 💡 Principales hallazgos

- **Entertainment** domina el Trending global con el 27,9% del total de videos, más del doble que cualquier otra categoría.
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

3. Abre los notebooks en orden:
```bash
jupyter notebook
```
   - Primero: `procesamiento.ipynb`
   - Luego: `eda_trending_completo.ipynb`

---

## 📂 Fuente de los datos

Dataset de YouTube Trending disponible públicamente. Contiene registros de videos en tendencia por región, fecha y categoría entre noviembre 2017 y junio 2018.

---

## 👤 Autor

Hecho con 💙 por **[Tu nombre]**  
[LinkedIn](#) · [GitHub](#)
