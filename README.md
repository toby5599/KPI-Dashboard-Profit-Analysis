# Proyecto KPIS-Dashboard

## Objetivos del proyecto
Este proyecto tiene como objetivo realizar un análisis exhaustivo de ganancias y pérdidas a través de un **dashboard** en **Power BI**. El análisis abarca los cuatro trimestres del año 2014 y se centra en establecer **KPIs** mediante umbrales y objetivos. Se explorarán las ganancias y pérdidas considerando diversos factores, como el tipo de producto, el segmento, el país, el descuento, el gasto por producto y la cantidad vendida.

El dashboard está diseñado para proporcionar una visualización clara y detallada de estos aspectos. Gracias a los distintos filtros disponibles, el usuario puede identificar qué factores están provocando pérdidas a la empresa. Esto permite descubrir áreas problemáticas y entender mejor dónde podría estar fallando la empresa en sus operaciones de ventas, facilitando la toma de decisiones estratégicas y la implementación de medidas correctivas.

[Dashboard online](https://app.powerbi.com/view?r=eyJrIjoiNmE5NWZhZmYtMGM2ZC00YzNmLThjMGItOWFmZDA5Zjg0MDNjIiwidCI6IjZiNzEzZTlhLTJhNGItNGMyYi1iZjc4LWRlODE2OGJjODdmMSIsImMiOjR9)

## KPIs Utilizados

### Profit Ratio

El Profit Ratio (o porcentaje de ganancia) mide qué porcentaje de las ventas totales se convierte en ganancias. Este KPI es importante porque indica la **eficiencia** con la que una empresa convierte sus ingresos en beneficios netos, lo cual es crucial para evaluar la rentabilidad de la empresa.

$$\text{Profit Ratio} = \left( \frac{\text{Profit}}{\text{Sales}} \right) \times 100$$

### Gross Margin

El Gross Margin (margen bruto) mide el porcentaje de ingresos que queda después de cubrir el costo de los bienes vendidos (COGS). Es un indicador clave para evaluar la **eficiencia** operativa, que revela la rentabilidad bruta de las ventas antes de considerar otros gastos operativos, financieros y tributarios. 

El Margen Bruto permite entender cuánto de cada dólar generado en ventas se convierte en ganancia bruta, y cuánto se destina a cubrir los costos de producción o adquisición. Por ejemplo, un margen bruto del 60% implica que por cada dólar de ingresos, $0.60 se convierten en ganancia bruta, mientras que $0.40 cubren los costos de fabricación.

$$\text{Gross Margin} = \left( \frac{\text{Gross Sales} - \text{COGS}}{\text{Gross Sales}} \right) \times 100$$

### Discount Percentage

El Discount Percentage mide el porcentaje de descuentos aplicados en relación con las ventas brutas. Este KPI es importante para evaluar el impacto de las estrategias de descuento en las ventas y los márgenes.

$$\text{Discount Percentage} = \left( \frac{\text{Discounts}}{\text{Gross Sales}} \right) \times 100$$

## Umbrales y Metas
Para evaluar el desempeño de los indicadores, establecí un valor objetivo (meta) o umbrales, que nos permita medir y comparar los resultados. 

### Profit ratio

En el caso del Profit Ratio, he definido los siguientes umbrales para clasificar el desempeño:
- *Menor o igual a 10: Deficiente*. El Profit Ratio es bajo, indicando una rentabilidad limitada.
- *De 10 a 15: Aceptable*. El Profit Ratio es adecuado, reflejando una rentabilidad razonable.
- *Mayor a 15: Sobresaliente*. El Profit Ratio es alto, indicando una excelente rentabilidad.

![image](https://github.com/user-attachments/assets/d60b4c7d-6234-4c92-8a07-75e4ce0d9446)


### Gross Margin

Para el caso del Gross Margin, he definido los siguientes umbrales para clasificar el desempeño:
- *Menor o igual a 10%: Alerta*. El margen bruto es bajo, indicando que los costos de producción son altos en comparación con las ventas, lo que afecta negativamente la rentabilidad.
- *De 10% a 30%: Deficiente*. El margen bruto se encuentra en un rango que puede indicar áreas de mejora en la gestión de costos. Aunque la empresa está cubriendo sus costos, existe potencial para optimizar los márgenes y mejorar la rentabilidad.
- *Mayor a 30%: Sobresaliente*. El margen bruto es alto, reflejando una excelente eficiencia en la gestión de costos y una sólida rentabilidad en las ventas.

### Discount Percentage

Para evaluar el impacto del Discount Percentage, es importante analizar cómo los descuentos afectan la rentabilidad y las pérdidas. En lugar de establecer objetivos específicos, Utilicé filtros para identificar cuándo los descuentos están generando pérdidas y cuándo no.

![image](https://github.com/user-attachments/assets/445ad282-a534-4772-ae96-eb100191e5b8)

## Previsualización del Dashboard
![image](https://github.com/user-attachments/assets/767d4f74-436a-4f18-8163-f55d590c2d89)
