# 🧨El “Silencio Explosivo”

Detección de Riesgo Latente mediante Kurtosis y Volumen Anómalo

## 📌Descripción

Este proyecto identifica uno de los patrones más raros y peligrosos del mercado: un aumento extremo del riesgo de cola (kurtosis) en un contexto de volumen anormalmente bajo y precio prácticamente inmóvil.

Este fenómeno, denominado “Silencio Explosivo”, suele aparecer antes de eventos binarios de gran impacto, como:
- Adquisiciones hostiles
- Fallos judiciales relevantes
- Decisiones regulatorias inesperadas
- En apariencia, el mercado está “muerto”. En realidad, está cargando una bomba estadística.
- Hipótesis de Mercado
- Cuando el volumen desaparece pero la kurtosis se dispara, el mercado está descontando un evento extremo que aún no es visible en el precio.

Este patrón rompe con la intuición clásica:

📉 No hay volatilidad visible

📊 No hay volumen

⚠️ Pero el riesgo de movimientos extremos es máximo

Es la calma absoluta antes de un movimiento de ±20% o más.

## 🧮Metodología

La consulta cruza indicadores técnicos, precios diarios y metadatos del ticker para detectar simultáneamente:
- Volumen extremadamente bajo
- Menor al 50% del volumen promedio histórico del ticker.
- Riesgo de cola extremo
- kurtosis > 8.0, indicando una distribución con eventos extremos altamente probables.
- Precio completamente comprimido
- Movimiento intradía menor al 1% (ausencia total de volatilidad visible).
- Solo cuando las tres condiciones ocurren al mismo tiempo, se activa la señal.

## 🚀Interpretación de Resultados

Los tickers devueltos por esta consulta representan riesgo asimétrico puro:

❌ No son activos para trading direccional clásico

⚠️ Son candidatos a eventos discontinuos

## 🎯Ideales para:

- Estrategias de opciones (straddles / strangles)
- Alertas de riesgo sistémico
- Análisis de información privilegiada implícita

## 💼Valor de Negocio

🔍 Detección temprana de eventos extremos sin depender de noticias

🛡️ Protección de carteras ante shocks ocultos

🧠 Ventaja informacional frente a modelos basados solo en volatilidad histórica

Este tipo de señal no aparece en indicadores tradicionales y suele ser ignorada por traders minoristas.

## ⚠️Advertencia

- Este patrón no indica dirección, solo probabilidad de ruptura violenta.
- Debe usarse como alerta de riesgo, no como señal directa de compra o venta.

## 👤Autora
Flavia Hepp Proyecto de SQL aplicó un análisis de riesgo basado en eventos.
