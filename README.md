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
├── docs/
│   └── dashboard.png
│
├── Sales_and_Supply_Chain_Dashboard.xlsx
│
└── README.md
