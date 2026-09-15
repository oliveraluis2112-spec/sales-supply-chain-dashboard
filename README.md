# Sales & Supply Chain Dashboard

## Descripción del Proyecto
Proyecto de análisis de datos y business intelligence enfocado en evaluar el desempeño comercial, la rentabilidad y la eficiencia operativa dentro de la cadena de suministro (Supply Chain).

El proyecto fue desarrollado utilizando **Microsoft Excel, Power Query y Power Pivot**, abarcando desde la extracción, transformación y limpieza de datos (ETL) hasta el modelado relacional en estrella, cálculo de indicadores mediante medidas DAX y la construcción de un dashboard ejecutivo e interactivo.

---

## Problema de Negocio
En la gestión comercial y de cadena de suministro es fundamental monitorear el rendimiento de los productos, regiones y fuerza de ventas para identificar desviaciones en los márgenes de ganancia e ineficiencias operativas.

- Comportamiento y tendencia de la facturación histórica.
- Distribución de márgenes de ganancia por línea de producto y subcategoría.
- Concentración de ventas según el segmento de cliente.
- Rendimiento comparativo por vendedor y zona geográfica.
- Identificación de productos estrella frente a productos de bajo margen.

---

## Fuente de Datos y Estructura
Dataset transaccional obtenido de Kaggle:  
[Retail & Supply Chain Sales Dataset – Kaggle](https://www.kaggle.com/code/mahmoudredagamail/retail-supply-chain-sales-dataset)

sales-supply-chain-dashboard/
│
├── data/
│   └── raw_data.csv                    # Dataset original extraído de Kaggle
├── docs/
│   └── dashboard.png                   # Captura de pantalla del Dashboard
├── Sales_and_Supply_Chain_Dashboard.xlsx # Libro en Excel con Power Query, Power Pivot y DAX
└── README.md                           # Documentación principal

# Análisis de Negocio y Hallazgos Principales

## Indicadores Generales (KPIs)

| Indicador | Valor Consolidado |
| :--- | :---: |
| **Ventas Totales** | $2,297,201 |
| **Ganancias Totales** | $286,397 |
| **Margen Total** | 12.5% |
| **Órdenes Procesadas** | 5,009 |

---

## Resumen de Hallazgos Clave
- **Rentabilidad por Subcategoría:** **Copiers** lidera en ganancias ($55,618), seguida por **Phones** ($44,516) y **Accessories** ($41,937).
- **Producto Estrella:** *Canon imageCLASS 2200 Advanced Copier*, generando **$25,200** en ganancias netas.
- **Rendimiento Comercial y Regional:** Región **West** lidera las ventas, impulsada por Anna Andreadi ($725,458 en ventas y $108,418 en ganancias).
- **Concentración de Mercado:** Segmento **Consumer** representa el **50%** de la facturación ($1,161,401).
- **Categoría Principal:** **Technology** representa el **37%** ($836,154) de las ventas totales.

---

# Conclusiones y Tecnologías Utilizadas

La solución permite centralizar la información para respaldar decisiones ejecutivas sobre facturación y márgenes por zona geográfica.

- **Herramientas:** Microsoft Excel, Power Query, Power Pivot.
- **Técnicas:** Esquema en estrella, fórmulas DAX, segmentadores interconectados y maquetación de dashboard.

---

# Autor

**Luis Olivera**  
Análisis de Datos, Business Intelligence y Automatización de Procesos
