[← Clase](../README.md)

# Sensores y acondicionamiento de señal

## Transducción

LDR cambia resistencia con luz, NTC con temperatura. Otros sensores entregan corriente o tensión. Sensibilidad, resolución, exactitud y precisión difieren; calibración usa referencias conocidas.

## Divisor

R fijo arriba y Rs abajo: Vout=VccRs/(R+Rs). NTC abajo disminuye Vout al calentar; relación no lineal e impedancia R paralelo Rs puede requerir buffer.

## ADC

Filtro reduce ruido y limita banda. ADC N bits: paso nominal Vref/2^N. Nyquist exige muestreo mayor que doble máxima frecuencia de señal limitada en banda; dejar margen para filtro real.

## Ejemplo resuelto

3,3 V, R=10 kΩ: Rs=10 kΩ da 1,65 V; 5 kΩ da 1,10 V. ADC 10 bits: paso≈3,22 mV.

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué un cambio pequeño puede no cambiar código?
