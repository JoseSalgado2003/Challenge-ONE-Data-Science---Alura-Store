# 📊 Alura Store Latam: Análisis de Rendimiento de Ventas

¡Bienvenido al primer desafío de Data Science! En este proyecto, asumo el rol de analista de datos para ayudar al **Sr. Juan** a tomar una decisión estratégica: ¿Qué tienda de su cadena, **Alura Store**, debería vender para financiar su nuevo emprendimiento?

A través del análisis de datos de ventas, reseñas y logística de 4 sedes diferentes, identificaremos la menos eficiente para fundamentar una recomendación basada 100% en datos.

## 🎯 Propósito del Análisis
El objetivo principal es evaluar el desempeño comparativo de las tiendas de Alura Store para maximizar el retorno de inversión del Sr. Juan. El análisis se centra en:
* **Rentabilidad:** Facturación total por tienda.
* **Satisfacción del cliente:** Promedio de calificaciones.
* **Logística:** Costos de envío promedio.
* **Popularidad:** Volumen de ventas por categoría y producto.

## 📁 Estructura del Proyecto
El proyecto se compone de un Notebook de Jupyter que integra la extracción, limpieza y visualización de datos:

* `AluraStoreLatam.ipynb`: Notebook principal que contiene el código en Python, los gráficos generados y la conclusión final.
* **Fuentes de datos:** Conexión directa a 4 archivos CSV alojados en GitHub que representan las transacciones de cada tienda.

## 🛠️ Herramientas Utilizadas
* **Python 3**
* **Pandas:** Manipulación y limpieza de estructuras de datos.
* **Matplotlib / Seaborn:** Creación de visualizaciones interactivas y estáticas.
* **Google Colab:** Entorno de desarrollo.

---

## 📈 Insights y Visualizaciones
*A continuación, se describen los pilares del análisis realizado en el notebook:*

### 1. Análisis de Facturación
Se comparó el ingreso bruto de cada sede para identificar cuál genera el menor flujo de caja.

### 2. Ventas por Categoría
Identificamos si una tienda depende excesivamente de un solo tipo de producto (ej. Electrónicos vs. Muebles) y cómo varía la demanda entre ciudades como Bogotá, Medellín, Cali y Cartagena.
> 
### 3. Calificación y Experiencia de Usuario
No todo es dinero. Analizamos la **Calificación Promedio** para detectar problemas de servicio al cliente o calidad de producto que podrían estar dañando la marca.

### 4. Eficiencia Logística
Calculamos el **Costo de Envío Promedio**. Una tienda con costos logísticos muy altos en comparación con sus ventas es una candidata ideal para ser vendida.

---

## 🚀 Instrucciones de Ejecución
Para replicar este análisis, sigue estos pasos:

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/alura-store-latam.git](https://github.com/tu-usuario/alura-store-latam.git)
    ```
2.  **Abrir en Google Colab o Jupyter:**
    * Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com/).
    * O ejecuta localmente con `jupyter notebook`.
3.  **Instalar dependencias (si es local):**
    ```bash
    pip install pandas matplotlib seaborn
    ```
4.  **Ejecutar las celdas:** El notebook está configurado para descargar automáticamente los datasets desde los links de Alura Latam.

## 📝 Conclusión y Recomendación
Al final del notebook, encontrarás el reporte ejecutivo dirigido al Sr. Juan, detallando qué tienda presenta los indicadores más bajos de rendimiento (menores ventas y mayor costo operativo) y por qué deshacerse de esa unidad es la mejor decisión financiera.

---
Desarrollado con ❤️ para el Challenge de Alura Latam.
