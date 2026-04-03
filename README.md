# sales-analysis-powerbi-sql

# 📊 Análisis de Ventas: Identificación de Clientes VIP y Oportunidades de Crecimiento

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de ventas y clientes a partir de un dataset tipo Superstore, con el fin de identificar oportunidades de negocio, segmentar clientes y evaluar la rentabilidad.

Se desarrolló un flujo completo de análisis utilizando:

- PostgreSQL para consultas y transformación de datos  
- Power BI para visualización e interpretación  
- DAX para métricas de negocio  
- Python para limpieza de datos  

---

## Objetivos

- Identificar los clientes más valiosos (VIP)  
- Analizar la relación entre ventas y rentabilidad  
- Detectar patrones de comportamiento en el tiempo  
- Proponer estrategias basadas en datos  

---

## Dataset

Se utilizó un dataset de ventas tipo retail que incluye información sobre:

- Clientes  
- Categorías de productos  
- Fechas de compra  
- Ventas  

Se generaron variables adicionales como:

- `Profit` (ganancia)  
- `Quantity` (cantidad)  

---

## Análisis Realizado

### SQL (PostgreSQL)

Se realizaron consultas para:

- Ventas totales y ganancia  
- Top clientes por ventas  
- Clientes más rentables  
- Ventas por categoría  
- Tendencia mensual de ventas  
- Segmentación de clientes (VIP, Medio, Bajo)  

---

### 🔹 Segmentación de Clientes

Se clasificaron los clientes según su nivel de gasto:

- 🟢 **VIP** → Alto valor  
- 🟡 **Medio** → Valor intermedio  
- 🔴 **Bajo** → Bajo valor  

Esto permitió identificar la concentración de ingresos en un grupo reducido de clientes.

---

## 📊 Dashboard (Power BI)

El dashboard incluye:

### KPIs
- Ventas totales  
- Ganancia total  
- Ticket promedio  
- % de ventas generadas por clientes VIP  

### Visualizaciones
- Evolución mensual de ventas  
- Ventas por categoría  
- Top 10 clientes  
- Distribución de ingresos por segmento  
- Comparación ventas vs ganancia  

---

## Insights Clave

- Los clientes VIP, aunque representan una minoría, generan una proporción significativa de los ingresos  
- Existe una alta dependencia en un grupo reducido de clientes  
- La categoría Tecnología lidera en ventas y rentabilidad  
- Se identifican oportunidades para convertir clientes de valor medio en clientes VIP  

---

## Recomendaciones

- Implementar estrategias de fidelización para clientes VIP  
- Diseñar campañas para aumentar el ticket promedio  
- Enfocar esfuerzos en la conversión de clientes de valor medio  
- Analizar productos con alta venta pero baja rentabilidad  

---

## Tecnologías Utilizadas

- PostgreSQL  
- Power BI  
- DAX  
- Python  

---

## Dashboard

![Dashboard](./dashboard.png)



##  Autor

**Whendy Yohaly Ocampo Mejía**  
Ingeniería Matemática | Análisis de Datos  
