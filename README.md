# 🛒 Challenge Data Science LATAM – Alura Store

## 📘 Descripción del proyecto

Este proyecto forma parte del **Challenge de Data Science de Alura LATAM**, desarrollado en el marco del programa **Oracle Next Education (ONE)**.  
El objetivo principal es ayudar al **Sr. Juan**, dueño de la cadena **Alura Store**, a **decidir qué tienda vender** para iniciar un nuevo emprendimiento.

Se realizó un análisis de datos de **cuatro tiendas** (Tienda 1, Tienda 2, Tienda 3 y Tienda 4), evaluando su desempeño en base a:

- 💰 **Ingresos totales**
- 🛍️ **Categorías de productos más y menos vendidas**
- ⭐ **Calificación promedio de los clientes**
- 📦 **Productos más y menos vendidos**
- 🚚 **Costo promedio de envío**

El objetivo final fue **identificar la tienda menos eficiente** y justificar la recomendación con base en el análisis exploratorio y las visualizaciones generadas.

El desafío consistió en analizar los datos proporcionados y generar un informe final dentro de un **notebook de Google Colab**, donde se presentaran:

- Visualizaciones relevantes
- Comparativas entre tiendas
- Conclusión final justificada
- Recomendación sobre qué tienda vender


## 🧩 Estructura del proyecto

📂 alura-store-challenge/
│
├── 📄 README.md → Documentación principal del proyecto
├── 📓 alura_store_analysis.ipynb → Notebook del análisis completo (Google Colab)
├── 📂 data/ → Archivos CSV de las cuatro tiendas
│ ├── tienda_1.csv
│ ├── tienda_2.csv
│ ├── tienda_3.csv
│ └── tienda_4.csv
└── 📁 img/ → (Opcional) Gráficos exportados o capturas de visualizaciones


---

## ⚙️ Instalación y dependencias

Para ejecutar este proyecto localmente o en **Google Colab**, asegúrate de tener instaladas las siguientes dependencias:

pip install pandas matplotlib seaborn folium

-----

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   
   git clone https://github.com/lErick3000/challenge-alura-2.git
   cd alura-store-challenge

2. Abre el archivo principal del análisis:

    jupyter notebook alura_store_analysis.ipynb

     o bien, ejecútalo directamente en Google Colab.


---

3. Dentro del notebook encontrarás:
   - Limpieza e integración de datos  
   - Análisis descriptivo  
   - Visualizaciones comparativas  
   - Conclusión final y justificación  
   - (Extra) Análisis geográfico de ventas  

Cada sección está documentada y comentada para facilitar su comprensión.

## 🌍 Extra: análisis geográfico de las ventas

Además del análisis principal, se desarrolló una **actividad extra opcional** enfocada en el estudio geográfico de las ventas utilizando las columnas **`lat`** y **`lon`**.

Mediante bibliotecas como **Matplotlib**, **Seaborn** y **Folium**, se generaron:
- Gráficos de dispersión de las ventas por ubicación  
- Mapas de calor interactivos (**Heatmaps**)  
- Análisis regional de precios promedio y calificaciones  

Estos resultados permitieron identificar **zonas con mayor concentración de ventas** y observar cómo la ubicación geográfica influye en el rendimiento de cada tienda.

El análisis evidenció diferencias regionales que complementan la comprensión del comportamiento de los clientes y la logística de envío.

## 🏁 Resultados y conclusiones

Después de comparar todos los indicadores, los resultados mostraron que:

> 🔴 **La Tienda 4 es la menos eficiente**  
> Presenta los ingresos más bajos, una calificación promedio ligeramente inferior y menor volumen de ventas.  
> Aunque su costo de envío es el más bajo, no logra compensar su bajo desempeño general.

**Recomendación final:**  
Se sugiere que el **Sr. Juan venda la Tienda 4** y conserve las tiendas con mayor rendimiento (especialmente Tienda 1 y Tienda 2), ya que muestran mejores ingresos y una base de clientes más satisfecha.

## 🧠 Tecnologías utilizadas

- **Python 3**
- **Pandas** → Limpieza y manipulación de datos  
- **Matplotlib** → Gráficos de líneas y barras  
- **Seaborn** → Análisis visual y correlaciones  
- **Folium** → Mapas interactivos (heatmaps geográficos)  
- **Google Colab / Jupyter Notebook**

---

## 💡 Posibles mejoras

- Implementar un **modelo predictivo** para estimar ingresos futuros por tienda.  
- Aplicar **segmentación de clientes** según ubicación o comportamiento de compra.  
- Desarrollar **dashboards interactivos** con Plotly o Streamlit.  
- Incluir un análisis temporal de tendencias de venta.

## 👨‍💻 Autor

**Erick Honorio**  
🌐 [https://github.com/lErick3000](https://github.com/lErick3000)

Proyecto desarrollado como parte del **Challenge Data Science LATAM – Alura + Oracle Next Education (ONE)**.

---

⭐ *Si te gustó este proyecto, considera dejar una estrella en el repositorio para apoyarlo.*


