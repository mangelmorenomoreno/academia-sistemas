[← Clase](../README.md)

# Comparadores e histéresis

## Comparador

Decide cuál entrada tiene mayor tensión; salida alta o baja. Algunas salidas abiertas requieren pull-up. Operacional no siempre es comparador rápido.

## Histéresis

Schmitt inversor V+=βVout+(1−β)Vref. Umbral alto βVH+(1−β)Vref; bajo βVL+(1−β)Vref. Al superar alto, salida baja; al bajar de inferior, alta.

## Memoria

Entre umbrales, estado depende de historia. Banda mayor que perturbaciones reduce transiciones espurias, pero reduce sensibilidad cerca umbral.

## Ejemplo resuelto

VH=5 V, VL=0 V, Vref=2,5 V, β=0,2: umbrales 3 V y 2 V.

![Modelo](../recursos/01.svg)

**Reto:** ¿Qué salida hay en 2,5 V tras superar 3 V?
