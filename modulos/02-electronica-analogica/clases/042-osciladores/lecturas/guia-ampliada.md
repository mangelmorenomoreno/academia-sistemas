[← Clase](../README.md)

# Osciladores y temporización

## Arranque

Oscilador convierte energía DC en señal variable. Condición inicial o ruido inicia cambio. Lazo sinusoidal lineal sostenido: fase 0° módulo 360° y magnitud cercana a uno. Arranque exige crecimiento; no linealidad limita amplitud.

## Relajación

Schmitt y RC cargan y descargan entre umbrales. Salida ±Vs y umbrales ±βVs: T=2RC·ln((1+β)/(1−β)). Salida cuadrada, Vc exponencial por tramos.

## Estabilidad

Tolerancia, temperatura, ruido y retardo alteran frecuencia. Cristal aprovecha resonancia mecánica. Distingue periodo, frecuencia, ciclo útil y jitter.

## Ejemplo resuelto

10 kΩ, 100 nF, β=1/3: T≈1,386 ms y f≈721 Hz.

![Modelo](../recursos/01.svg)

**Reto:** ¿Qué cambia al duplicar C?
