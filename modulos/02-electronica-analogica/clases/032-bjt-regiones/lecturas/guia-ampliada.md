[← Clase](../README.md)

# Transistor BJT: regiones y polarización

## Estructura

NPN tiene emisor N, base P delgada y colector N. En activa BE directa, BC inversa; muchos electrones llegan a colector y otros recombinan. IC≈βIB es aproximado.

## Regiones

Corte: corriente pequeña; activa: corriente controlada; saturación: ambas uniones directas, corriente limitada por circuito. VCE(sat) varía. Fuente del colector aporta energía.

## Polarización

Resistor de emisor estabiliza punto Q: IE aumenta, VE sube y VBE baja si VB casi fijo. β varía; revisar potencia VCE·IC y margen de salida.

## Ejemplo resuelto

5 V, RC=1 kΩ, IB=20 µA, β=100: IC≈2 mA, VCE≈3 V con emisor a tierra.

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué no diseñar con β exacto?
