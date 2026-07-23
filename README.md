# Análisis de Retención por Cohortes

## 📌 Contexto

E-commerce de textiles para el hogar con años de historial de ventas, pero sin visibilidad clara sobre cómo se comportaban los clientes después de su primera compra: ¿volvían a comprar? ¿cuándo? ¿qué porcentaje se perdía con el tiempo?

## 🎯 Objetivo

Entender el comportamiento de compra recurrente de los clientes a lo largo del tiempo para:
- Detectar en qué momento del ciclo de vida del cliente se concentra la mayor caída de retención
- Evaluar el impacto de campañas o cambios en la tienda sobre la fidelización
- Priorizar en qué etapa del funnel de retención enfocar los recursos de marketing

## 🔍 Metodología

Se construyó un análisis de **cohortes de retención**, agrupando a los clientes según el mes de su primera compra y siguiendo su comportamiento en los meses siguientes:

1. Limpieza y estructuración de datos históricos de pedidos por cliente
2. Agrupación de clientes en cohortes mensuales según fecha de primera compra
3. Cálculo del porcentaje de cada cohorte que volvió a comprar en cada mes posterior
4. Visualización en tabla de calor (heatmap) para identificar patrones de caída y meses de mejor retención

## 📊 Resultado

- Se identificó con claridad el período crítico en el que se concentra la mayor pérdida de clientes después de la primera compra
- El análisis permitió priorizar acciones de retención (por ejemplo, comunicaciones o incentivos) específicamente en esa ventana de tiempo, en lugar de aplicar el mismo esfuerzo a lo largo de todo el ciclo de vida del cliente
- Quedó como proceso mensual recurrente para monitorear la salud general de la retención de la marca

## 🛠️ Herramientas utilizadas

Google Sheets · Exportaciones de plataforma e-commerce

---
*Nota: los datos y el nombre de marca en este caso fueron anonimizados/ficcionalizados por confidencialidad. La metodología y los tipos de hallazgos reflejan trabajo real.*# retencion-cohortes
