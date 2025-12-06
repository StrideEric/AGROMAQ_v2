# 📊 Proyecto Power BI – Análisis de Ventas para AGROMAQ
## ⭐ Dashboard profesional desarrollado en Power BI para el análisis de ventas, clientes, productos y sucursales.

Este proyecto forma parte de un laboratorio práctico orientado a aplicar un flujo completo de BI: ETL → Modelado → DAX → Dashboard.

### 🎯 Objetivo del Proyecto
Crear un informe interactivo en Power BI que permita analizar:
* Rendimiento de ventas por sucursal
* Comportamiento de clientes
* Participación por tipo de producto
* Distribución geográfica
* KPIs estratégicos para la toma de decisiones

### 🛠️ 1. ETL – Extracción, Transformación y Carga
Se conectaron 5 fuentes de datos distintas:
* Ventas
* Productos
* Clientes
* Empleados
* Sucursales

Transformaciones realizadas <br>
✔ Renombrado de columnas <br>
✔ Cambio de tipos de datos <br>
✔ Eliminación de duplicados <br>
✔ Columnas condicionales <br>
✔ Combinación de consultas <br>
✔ Corrección de datos inconsistentes <br>

Se aseguraron datos limpios y listos para modelado.

### 🧩 2. Modelado de Datos (Esquema en Estrella)
El modelo está formado por:
◆ Tabla de hechos:
* fact_ventas
◆ Dimensiones:
* clientes_sucia
* productos_sucia
* empleados
* sucursales
* DimDate

✔ Relaciones 1:* correctamente definidas <br>
✔ Calendario creado con DAX <br>
✔ Inteligencia de tiempo habilitada <br>

### ➕ 3. Medidas DAX Implementadas
Ejemplos de medidas (entre otras):
* Cantidad de Ventas = SUM(fact_ventas[Cantidad])
* % Ventas Maquinarias
* % Ventas Repuestos
* Categoría Top %
* Total Ventas
* Clientes Únicos

Incluye expresiones DAX de KPIs y cálculos avanzados.

### 📈 4. Dashboard final (Páginas de Informe)
#### Página 1: Resumen Ejecutivo
- Mapa por provincia
- KPI de ventas
- Ventas vs clientes únicos
- Clientes por provincia
- Filtro dinámico de año, sucursal y provincia

#### Página 2: Análisis de Productos
- Total de ventas por tipo de producto
- Unidades vendidas por modelo y marca
- Categorías más vendidas
- Ventas por quarter
- Segmentación por marcadores
#### Página 3: Análisis de Clientes y Sucursales
- Ingresos por sucursal
- Clientes únicos por sucursal
- Comportamiento geográfico
- Comparativas visuales entre regiones


### 🚀 Tecnologías utilizadas

- Power BI Desktop
-  Power Query
-  DAX
-  Modelado dimensional (estrella)
-  Visualizaciones avanzadas
-  Inteligencia de datos