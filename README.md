# Challenge_analisis_datos-


## Propósito
Este proyecto tiene como objetivo ayudar al Sr. Juan a decidir qué tienda de la cadena **Alura Store** debe vender para financiar un nuevo emprendimiento.  
Se realizó un análisis comparativo de las 4 tiendas considerando:
- Ingresos totales
- Categorías de productos más y menos vendidas
- Calificaciones promedio de clientes
- Productos más y menos vendidos
- Costos de envío promedio

El resultado final es una recomendación clara y objetiva sobre qué tienda vender, respaldada por datos y visualizaciones.
## Estructura del proyecto
- **/data** → Archivos con los datos de ventas, reseñas y costos de envío de las tiendas.  
- **/notebooks** → Jupyter Notebooks con el análisis exploratorio y generación de gráficos.  
- **/report** → Informe final en formato Markdown con hallazgos y recomendación.  
- **README.md** → Documento de presentación del proyecto.

  
### Ingresos por tienda
Gráfico de pie que muestra los ingresos totales de cada tienda.  
**Insight:** La Tienda 4 genera el menor ingreso (≈23.6% del total), lo que la convierte en la candidata más lógica para la venta.

### Calificaciones promedio
Gráfico comparativo de las calificaciones de clientes.  
**Insight:** La Tienda 3 tiene la mejor valoración (4.05/5), mientras que la Tienda 1 tiene la más baja (3.98/5). La Tienda 4 se mantiene en un nivel intermedio (4.00/5).

### Costos de envío
Gráfico de líneas mostrando el costo promedio de envío por tienda.  
**Insight:** La Tienda 4 tiene el costo de envío más bajo, pero esta ventaja no compensa su menor ingreso y desempeño general.



## Requisitos previos
- **Python 3.9+**
- **Jupyter Notebook** instalado
- Librerías necesarias:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

## Recomendación final
Con base en los datos y gráficos generados, se recomienda vender la Tienda 4, ya que:
- Es la que menos aporta a los ingresos totales.
- Su calificación promedio no destaca frente a las demás.
- No aporta diferenciación estratégica en categorías ni productos.
- Su venta libera capital con el menor impacto en la facturación global.

Proyecto elaborado por Mijael, en el marco de análisis académico y práctico de datos de negocio.



