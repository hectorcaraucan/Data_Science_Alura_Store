Análisis de rendimiento comercial - Alura Store
Toma de decisiones basada en datos para la optimización de activos retail.
📖 Descripción del Proyecto
Este proyecto simula un escenario de consultoría de datos real para la cadena minorista Alura Store. El propietario, el Sr. Juan, necesita capital para un nuevo emprendimiento y debe vender una de sus 4 tiendas actuales.
El objetivo de este análisis es procesar los datos históricos de ventas, logística y satisfacción del cliente para identificar cuál es la tienda menos eficiente y generar una recomendación estratégica fundamentada en datos cuantificables.
📂 Estructura del Proyecto
El repositorio está organizado de la siguiente manera:
Plaintext
├── data/                   # Archivos CSV con los datos crudos
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
├── notebooks/              # Cuadernos de análisis
│   └── AluraStoreLatam.ipynb
├── reports/                # Informes y recursos adicionales
│   └── Data_Science_Alura_Store.pdf
├── img/                    # Gráficos generados 
└── README.md               # Documentación del proyecto
🔍 Análisis Realizado
Para llegar a la conclusión final, se evaluaron 5 dimensiones clave (KPIs) para cada una de las 4 tiendas:
1.	Facturación Total: Ingresos brutos acumulados.
2.	Volumen por Categoría: Identificación de nichos de mercado (Muebles, Tecnología, etc.).
3.	Satisfacción del Cliente: Promedio de calificaciones (Rating 1-5).
4.	Productos Top: Artículos más y menos vendidos (Pareto).
5.	Eficiencia Logística: Costo promedio de envío.
🚀 Resultados e Insights Clave
Tras el procesamiento de los datos con Pandas y la visualización con Matplotlib, se obtuvieron los siguientes hallazgos:
1. Disparidad en Ingresos
Se detectó una brecha de facturación significativa. Mientras la Tienda 1 lidera el mercado con $1,150M, la Tienda 4 se encuentra rezagada con $1,038M.
 
2. La paradoja del envío
Aunque la Tienda 4 ofrece los costos de envío más económicos del grupo ($23k promedio), esto no ha sido suficiente para impulsar su volumen de ventas frente a competidores con envíos más costosos pero catálogos más atractivos.
3. Recomendación Final
📢 Decisión Estratégica: Se recomienda poner en venta la Tienda 4.
Justificación: Es el activo con menor rendimiento financiero (menor facturación histórica) y menor ticket promedio, lo que la convierte en la candidata ideal para desinversión con el fin de liberar capital.
🛠️ Instrucciones de ejecución
Para replicar este análisis en tu máquina local o en la nube:
Google Colab (Recomendado)
1.	Sube el archivo AluraStoreLatam.ipynb a tu Google Drive.
2.	Sube los 4 archivos CSV (tienda_1.csv, etc.) al almacenamiento de sesión del notebook.
3.	Ejecuta todas las celdas secuencialmente.
🤝 Contribuciones
Este es un proyecto educativo. Si encuentras formas de optimizar el código o nuevas visualizaciones interesantes, ¡siéntete libre de hacer un Fork y enviar un Pull Request!
✒️ Autor
Héctor Caraucán - Analista de Datos en formación.
