# Sales & Supply Chain Dashboard

## Descripción del proyecto

Proyecto de análisis de datos y Business Intelligence enfocado en evaluar el desempeño comercial, la rentabilidad y el comportamiento de las ventas desde diferentes perspectivas del negocio.

El análisis fue desarrollado utilizando **Microsoft Excel, Power Query y Power Pivot**, abarcando desde la extracción, transformación y limpieza de datos hasta el modelado dimensional, creación de medidas DAX y desarrollo de un dashboard ejecutivo e interactivo.

El objetivo principal es identificar patrones relacionados con **ventas, ganancias, márgenes, productos, segmentos de clientes, vendedores y regiones**, con el fin de detectar oportunidades y puntos de atención dentro del desempeño comercial.

---

## Problema de negocio

En la gestión comercial es importante contar con información que permita evaluar el desempeño de las ventas y la rentabilidad de los productos, clientes, vendedores y regiones.

Entre los principales aspectos analizados se encuentran:

* Evolución histórica de las ventas.
* Rentabilidad por categoría y subcategoría.
* Desempeño de productos.
* Distribución de ventas por segmento de cliente.
* Rendimiento de vendedores.
* Desempeño por región geográfica.
* Identificación de productos con mayor contribución a las ganancias.
* Identificación de categorías y productos con menor rentabilidad.

A partir de estos indicadores se busca identificar los principales factores que contribuyen al desempeño comercial y aquellos que podrían requerir una revisión más detallada.

---

## Objetivo

Analizar los datos transaccionales de ventas mediante Excel y sus herramientas de Business Intelligence para responder preguntas de negocio relacionadas con:

* Evolución de las ventas a través del tiempo.
* Ventas y ganancias por categoría.
* Rentabilidad por subcategoría.
* Productos con mayor contribución a las ganancias.
* Ventas por segmento de cliente.
* Desempeño de vendedores.
* Ventas y ganancias por región.
* Distribución de las ventas por categoría.
* Identificación de los principales productos y categorías.
* Análisis de los principales indicadores comerciales.

---

## Dataset

Para el desarrollo del proyecto se utilizó un dataset transaccional de ventas disponible en Kaggle.

[Retail & Supply Chain Sales Dataset – Kaggle](https://www.kaggle.com/code/mahmoudredagamail/retail-supply-chain-sales-dataset)

El dataset contiene información relacionada con órdenes de venta, productos, categorías, subcategorías, clientes, segmentos, vendedores, regiones, ventas y ganancias.

### Principales variables

| Variable | Descripción |
| -------- | ----------- |
| `Order ID` | Identificador de la orden |
| `Order Date` | Fecha de la orden |
| `Product Name` | Nombre del producto |
| `Category` | Categoría del producto |
| `Sub-Category` | Subcategoría del producto |
| `Segment` | Segmento del cliente |
| `Sales` | Valor de ventas |
| `Profit` | Ganancia generada |
| `Region` | Región geográfica |
| `Salesperson` | Vendedor |

---

## Estructura del proyecto

```text
sales-supply-chain-dashboard/
│
├── data/
│   └── raw_data.csv
│
├── Dashboard/
│   └── Sales_and_Supply_Chain_Dashboard.xlsx
│
├── docs/
│   └── dashboard.png
│
└── README.md
```

---

# Proceso de análisis

## 1. Extracción y carga de datos

Se utilizó un dataset transaccional de ventas como fuente principal del análisis.

El archivo CSV fue incorporado al entorno de Excel para iniciar el proceso de preparación y transformación de los datos.

---

## 2. Limpieza y transformación

Se utilizó **Power Query** para realizar el proceso de preparación de los datos.

Entre las principales transformaciones realizadas se encuentran:

* Revisión de la estructura de los datos.
* Validación de tipos de datos.
* Tratamiento de valores nulos.
* Limpieza de registros.
* Transformación de columnas.
* Preparación de los datos para el modelado.
* Validación de la información antes de cargarla al modelo.

---

## 3. Modelado de datos

Se utilizó **Power Pivot** para construir un modelo dimensional bajo un esquema estrella.

El modelo permite organizar la información de ventas y relacionarla con las diferentes dimensiones utilizadas para el análisis.

La estructura facilita el análisis desde diferentes perspectivas como:

* Tiempo.
* Producto.
* Categoría.
* Cliente.
* Segmento.
* Vendedor.
* Región.

---

## 4. Creación de medidas

Se utilizaron medidas mediante **DAX** para calcular los principales indicadores comerciales.

Entre las principales métricas se encuentran:

* Ventas Totales.
* Ganancias Totales.
* Margen.
* Cantidad de Órdenes.
* Ventas por categoría.
* Ganancias por subcategoría.
* Ventas por región.
* Ventas por segmento.
* Ganancias por producto.
* Participación de ventas.

---

# Análisis de negocio

Se plantearon diferentes preguntas para analizar los principales indicadores comerciales.

## Pregunta 1. ¿Qué subcategorías generan mayores ganancias?

| Subcategoría | Ganancias |
| ------------ | --------: |
| Copiers | $55,618 |
| Phones | $44,516 |
| Accessories | $41,937 |

**Hallazgo:** Copiers presenta la mayor generación de ganancias, seguida por Phones y Accessories.

---

## Pregunta 2. ¿Cuál es el producto con mayor contribución a las ganancias?

El producto **Canon imageCLASS 2200 Advanced Copier** presenta la mayor contribución individual a las ganancias, con aproximadamente **$25,200**.

**Hallazgo:** Este producto representa una de las principales contribuciones individuales a la rentabilidad del negocio.

---

## Pregunta 3. ¿Qué región presenta el mayor desempeño comercial?

La región **West** presenta el mayor desempeño en ventas.

Dentro de esta región destaca la participación de **Anna Andreadi**, con:

* Ventas: **$725,458**
* Ganancias: **$108,418**

**Hallazgo:** La región West concentra un importante nivel de actividad comercial y presenta vendedores con una contribución significativa a las ventas y ganancias.

---

## Pregunta 4. ¿Qué segmento concentra la mayor facturación?

El segmento **Consumer** concentra aproximadamente el **50% de la facturación**, con **$1,161,401** en ventas.

**Hallazgo:** Consumer representa el principal segmento de clientes en términos de facturación.

---

## Pregunta 5. ¿Qué categoría representa la mayor proporción de las ventas?

La categoría **Technology** representa aproximadamente el **37% de las ventas totales**, alcanzando **$836,154**.

**Hallazgo:** Technology es la categoría con mayor participación dentro de las ventas analizadas.

---

# Indicadores principales

| Indicador | Valor |
| --------- | ----: |
| Ventas Totales | $2,297,201 |
| Ganancias Totales | $286,397 |
| Margen Total | 12.5% |
| Órdenes Procesadas | 5,009 |

---

# Principales hallazgos

A partir del análisis realizado se identificaron los siguientes puntos:

* **Copiers** presenta la mayor generación de ganancias entre las subcategorías analizadas.
* **Canon imageCLASS 2200 Advanced Copier** destaca como el producto con mayor contribución individual a las ganancias.
* La región **West** presenta un importante desempeño comercial.
* **Consumer** representa aproximadamente el 50% de la facturación.
* **Technology** representa aproximadamente el 37% de las ventas totales.
* Las ventas y ganancias presentan diferencias importantes según producto, categoría, segmento y región.

---

# Dashboard

El dashboard fue desarrollado en **Microsoft Excel** utilizando tablas dinámicas, gráficos, segmentadores y medidas DAX.

La solución permite interactuar con los principales indicadores y analizar la información desde diferentes perspectivas comerciales.

<img width="1803" height="757" alt="dashboard" src="https://github.com/user-attachments/assets/16e0627b-23e0-4bd7-9696-6cdd634b74d8" />

---

# Conclusiones

El análisis permitió desarrollar una solución de Business Intelligence orientada al seguimiento del desempeño comercial y la rentabilidad.

La integración de **Power Query, Power Pivot y DAX** permitió construir un flujo de trabajo que abarca la preparación de datos, modelado, cálculo de indicadores y visualización.

Los resultados permiten identificar las categorías, productos, segmentos, vendedores y regiones con mayor contribución al desempeño comercial.

El dashboard puede utilizarse como herramienta de apoyo para el análisis de ventas y rentabilidad, facilitando la identificación de oportunidades y puntos de atención para la gestión comercial.

---

# Tecnologías y herramientas utilizadas

## Herramientas

* Microsoft Excel
* Power Query
* Power Pivot
* DAX

## Técnicas

* Extracción y transformación de datos
* Limpieza de datos
* Modelado dimensional
* Esquema estrella
* Análisis exploratorio
* Creación de medidas DAX
* Tablas dinámicas
* Visualización de datos
* Dashboard interactivo

---

# Autor

**Luis Olivera García**

Análisis de Datos, Business Intelligence y Automatización de Procesos.
