[← Clase](../README.md)

# Rectificadores y filtrado: ondulación y diodos

## Rectificación

Un diodo conduce principalmente una semionda; puente de cuatro diodos alterna dos trayectorias con sentido de carga constante. Pierde aproximadamente dos caídas directas. Vp=√2·Vrms.

## Filtrado

C paralelo se carga cerca de picos y entrega corriente entre ellos. ΔV≈I/(fripple C) si ondulación pequeña; onda completa fripple=2f. Mayor C reduce ondulación pero eleva pulsos de recarga.

## Límites

Rectificar no es regular; salida depende de fuente, carga, diodos y temperatura. Revisar tensión inversa, corriente y calor. Solo fuente AC virtual de pocos voltios.

## Ejemplo resuelto

5 V RMS, 50 Hz, puente 0,7 V por diodo: pico≈5,67 V. I=10 mA y C=470 µF: ΔV≈0,213 V.

![Modelo](../recursos/01.svg)

**Reto:** ¿Qué pasa al duplicar C?
