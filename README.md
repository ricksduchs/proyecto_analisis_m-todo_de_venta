# Análisis de Métodos de Venta

## Descripción general
La empresa Pens and Printers busca identificar cuál de sus métodos de venta actuales es más efectivo para el lanzamiento de nuevos productos. Dado que los lanzamientos implican costos significativos, el objetivo es determinar qué método permite maximizar las ganancias y optimizar la estrategia comercial.

## Principales hallazgos
- La mayoría de los clientes es contactada mediante email, siendo el método con mayor revenue total  
- El método Email + Call presenta el mayor promedio de revenue por cliente, casi duplicando al siguiente  
- Email + Call también destaca en número de productos vendidos y visitas al sitio web  

## Herramientas
Python, Pandas, Matplotlib, Seaborn

## Recomendaciones
Dado que el método Email + Call genera el mayor revenue promedio  
Se recomienda utilizarlo como el método principal de contacto con clientes.  

Dado que el impacto debe evaluarse correctamente  
Se debe monitorear el promedio de revenue tanto a nivel global como por método de venta.  

A nivel global, se espera observar un aumento, ya que a medida que más clientes sean contactados mediante el método Email + Call, el promedio de revenue por venta será mayor, según los datos analizados.  

A nivel de método de venta, se debería observar un aumento en Email + Call o, al menos, que se mantenga estable, ya que, a medida que aumente el número de clientes en este método, incluso si su promedio se mantiene constante, el impacto global seguirá siendo positivo debido a su mayor promedio de revenue en comparación con los otros métodos.  

Es importante verificar que el número de clientes no disminuya al implementar este método, ya que una reducción podría afectar el revenue.  

Para mejorar la calidad del análisis  
Se recomienda especificar los productos vendidos en cada transacción y evitar datos faltantes en la columna de revenue para prevenir errores en los resultados.  
