[← Clase](../README.md)

# Análisis de tolerancias, temperatura y medición

## Tolerancia

10 kΩ ±5 % puede estar entre 9,5 y 10,5 kΩ en condiciones especificadas. En divisor evaluar extremos opuestos. Peor caso no equivale a probabilidad.

## Temperatura

R(T)≈R0(1+αΔT) en rango válido. ppm/°C son millonésimas por grado. Capacitores y semiconductores varían también con tensión y envejecimiento.

## Medición

Voltímetro tiene impedancia finita y carga nodo; amperímetro añade resistencia. Resolución no es exactitud; revisar calibración y especificación. No medir resistencia con energía.

## Ejemplo resuelto

Divisor 5 V con dos 10 kΩ ±5 %: mínimo 2,375 V, máximo 2,625 V.

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué ambos resistores +5 % conservan proporción?
