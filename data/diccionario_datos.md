# Diccionario de datos — ventas_diarias.csv

Ventas diarias de una categoría de bebidas en **una tienda de Cali** (1 de enero de 2023 a 31 de diciembre de 2025, 1.096 días). Datos **sintéticos**, creados para practicar pronóstico de demanda.

| Columna | Tipo | Significado |
|---|---|---|
| fecha | fecha (AAAA-MM-DD) | Día de la venta |
| ventas_unidades | entero | Unidades vendidas ese día (**variable a pronosticar**) |
| temperatura_c | decimal | Temperatura media del día en °C |
| lluvia_mm | decimal | Lluvia acumulada del día en milímetros |
| promocion | 0/1 | 1 si ese día hubo promoción |
| descuento_pct | entero | Porcentaje de descuento (0 si no hubo promoción) |
| festivo | 0/1 | 1 si es festivo en Colombia |
| precio_unitario | entero (COP) | Precio de venta ese día |

## Calidad de los datos
- Valores faltantes en temperatura y lluvia (sensor caído).
- Valores atípicos en ventas, tratados en el cuaderno.
