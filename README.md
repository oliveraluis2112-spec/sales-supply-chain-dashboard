# Sales & Supply Chain Dashboard

## Descripción del Proyecto

Proyecto de análisis de datos y business intelligence enfocado en evaluar el desempeño comercial, la rentabilidad y la eficiencia operativa dentro de la cadena de suministro (Supply Chain).

El proyecto fue desarrollado utilizando **Microsoft Excel, Power Query y Power Pivot**, abarcando desde la extracción, transformación y limpieza de datos (ETL) hasta el modelado relacional en estrella, cálculo de indicadores mediante medidas DAX y la construcción de un dashboard ejecutivo e interactivo.

El objetivo principal es identificar patrones relacionados con **ingresos por ventas, rentabilidad por categoría, eficiencia por canal de venta y desempeño por representante comercial**, con el fin de detectar oportunidades de optimización operativa y comercial.

---

## Problema de Negocio

En la gestión comercial y de cadena de suministro es fundamental monitorear el rendimiento de los productos, regiones y fuerza de ventas para identificar desviaciones en los márgenes de ganancia e ineficiencias operativas.

Entre los principales aspectos analizados se encuentran:

- Comportamiento y tendencia de la facturación histórica.
- Distribución de márgenes de ganancia por línea de producto y subcategoría.
- Concentración de ventas según el segmento de cliente.
- Rendimiento comparativo por vendedor y zona geográfica.
- Identificación de productos estrella frente a productos de bajo margen.

A partir de estos indicadores se busca proporcionar una herramienta centralizada que permita a la gerencia tomar decisiones basadas en datos.

---

## Objetivos

Analizar los datos transaccionales de ventas mediante modelado avanzado en Excel para responder preguntas de negocio relacionadas con:

- Tendencia temporal de ingresos y rentabilidad mensual.
- Subcategorías y productos que generan el mayor margen de ganancia.
- Rendimiento financiero por representante de ventas y región geográfica.
- Proporción de ingresos según la categoría y el segmento de mercado.
- Monitoreo del volumen total de órdenes procesadas y margen promedio global.

---

## Fuente de Datos

Para el desarrollo del proyecto se utilizó el dataset **Retail & Supply Chain Sales Dataset**, disponible en Kaggle.

[Retail & Supply Chain Sales Dataset – Kaggle](https://www.kaggle.com/code/mahmoudredagamail/retail-supply-chain-sales-dataset)[cite: 1]

El dataset contiene información detallada sobre transacciones comerciales, clientes, productos, categorías, áreas geográficas, vendedores, costos y márgenes de ganancia.

---

## Estructura del Repositorio

```text
sales-supply-chain-dashboard/
│
├── data/
│   └── raw_data.csv                    # Dataset original extraído de Kaggle
│
├── docs/
│   └── dashboard.png                   # Captura de pantalla en alta resolución del Dashboard
│
├── Sales_and_Supply_Chain_Dashboard.xlsx # Libro de trabajo en Excel con Power Query, Power Pivot y DAX
└── README.md                           # Documentación principal del proyecto
