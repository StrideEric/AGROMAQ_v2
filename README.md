# 📊 Proyecto Power BI – Análisis de Ventas para AGROMAQ
## ⭐ Dashboard profesional desarrollado en Power BI para el análisis de ventas, productos y sucursales

Este proyecto forma parte de un laboratorio orientado a aplicar un flujo completo de Business Intelligence: ETL → Modelado Dimensional → DAX → Storytelling con Power BI.

## 🎯 Objetivo del Proyecto
- Desarrollar un informe interactivo que permita comprender el comportamiento comercial de AGROMAQ a través de:
- Rendimiento de ventas por sucursal
- Identificación de sucursales más relevantes según su contribución al negocio
- Análisis de estacionalidad de ventas
- Participación por categoría de producto
- Distribución geográfica
- Indicadores clave para la toma de decisiones estratégicas
- El dashboard final está diseñado como un producto de datos, con narrativa visual clara y KPIs que guían al usuario hacia conclusiones accionables.

### 🛠️ 1. ETL – Extracción, Transformación y Carga
#### Se integraron 6 fuentes de datos:
- fact_ventas
- productos_sucia
- clientes_sucia
- empleados
- sucursales
- DimDate

#### Transformaciones realizadas <br>
✔ Renombrado y estandarización de columnas <br>
✔ Corrección de tipos de datos <br>
✔ Eliminación de valores duplicados <br>
✔ Limpieza de campos inconsistentes <br>
✔ Creación de nuevas columnas derivadas <br>
✔ Enriquecimiento del dataset (ampliación de compras, clientes y ventas) <br>
✔ Unionado y normalización de tablas <br>

El resultado es un dataset limpio, consistente y preparado para análisis avanzado.

### 🧩 2. Modelado de Datos – Esquema en Estrella
#### El modelo consta de:
- Tabla de hechos
- fact_ventas (ventas detalladas)
- clientes_sucia
- productos_sucia
- empleados
- sucursales
- DimDate

✔ Relaciones 1:N correctamente definidas <br>
✔ Tabla calendario creada en DAX <br>
✔ Inteligencia de tiempo habilitada (YTD, MTD, variaciones interanuales) <br>
✔ Modelo optimizado para rendimiento <br>

### ➕ 3. Medidas DAX Implementadas
#### Entre las medidas clave se incluyen:
- Total Ventas
- Cantidad de Ventas
- Ventas Maquinarias / Ventas Repuestos
- % Ventas por Categoría
- % Ventas Sucursal (participación relativa de la sucursal seleccionada)
- % Ventas Oct–Dic (análisis estacional)
- Clientes Únicos
- Ticket promedio

Estas medidas habilitan análisis comparativos, estacionales y de composición del negocio.

### 📈 4. Dashboard Final – Diseño y Contenido del Informe
El informe consta de una única página integrada, diseñada bajo principios de data storytelling y jerarquía visual, que permite recorrer la información desde la visión general hasta las conclusiones clave del negocio.

### 🟩 Contenido del Dashboard
1. Visión General (Zona Superior)
#### Incluye los KPIs estratégicos del negocio:
- Cantidad de Ventas
- Total de Ingresos
- % Ventas Oct–Dic (análisis de estacionalidad)
- % Ventas Sucursal (participación dinámica según la selección del usuario)
- Estos indicadores permiten evaluar rápidamente el rendimiento comercial y detectar patrones relevantes.

2. Análisis Detallado (Zona Central)
#### Visualizaciones principales:
- Total de Ventas por Mes (2023–2024)<br>
→ Permite identificar tendencias y el pico de ventas en noviembre-diciembre.

- Mapa por Provincia <br>
→ Muestra la distribución geográfica de ventas y presencia comercial.

- Ingresos por Sucursal <br>
→ Compara claramente el desempeño de Charata, Resistencia, Bandera y Quimilí.

- Ventas por Categoría de Producto <br>
→ Permite identificar las líneas más rentables del catálogo.

3. Narrativa Final (Zona Inferior)
#### Una tarjeta de texto sintetiza los hallazgos más importantes:

- Las sucursales Charata y Resistencia representan el 77.08% del total de ingresos.
- El periodo octubre–diciembre explica el 49.73% del ingreso anual.

Esta conclusión resume el comportamiento del negocio y facilita la toma de decisiones.

#### 🟧 Funcionalidades Clave del Dashboard

- Segmentadores interactivos: Año, Sucursal, Categoría, Tipo de Producto
- Diseño optimizado en una sola página
- Filtros laterales simplificados

Lectura guiada de izquierda a derecha: filtros → análisis → conclusiones

#### 🚀 Tecnologías utilizadas
- Power BI Desktop
- Power Query
- DAX
- Modelado Dimensional (Esquema en Estrella)
- Visualizaciones avanzadas y Data Storytelling

### 📝 Conclusión

Este proyecto demuestra la aplicación completa de técnicas de BI para generar un dashboard profesional, centrado en KPIs relevantes, narrativa clara y análisis accionable.
#### El resultado final permite identificar:
- Sucursales con mayor impacto en ventas
- Comportamiento estacional clave (Oct–Dic)
- Categorías más rentables
- Distribución geográfica del negocio

El informe está optimizado para ejecutivos que requieran tomar decisiones basadas en datos.