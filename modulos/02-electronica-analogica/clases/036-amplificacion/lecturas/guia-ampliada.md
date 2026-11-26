[← Clase](../README.md)

# Amplificación y ganancia, saturación y ruido

## Ganancia

Av=Vout/Vin, Ai=Iout/Iin, Ap=Pout/Pin. Tensión en dB=20log10 de magnitud de Av, potencia=10log10 Ap. Energía adicional proviene de fuente.

## Límites

Alimentación y corriente limitan excursión. Polos reducen ganancia y añaden fase a altas f; slew rate limita rapidez de salida incluso dentro de banda de pequeña señal.

## Ruido

Fluctuación no deseada, distinta de distorsión no lineal. SNR=10log10(Pseñal/Pruido). Amplificar también amplifica ruido y añade propio; reducir banda innecesaria disminuye ruido integrado.

## Ejemplo resuelto

0,1 V pico, Av=20: salida ideal 2 V pico, 26 dB. Límite ±1,5 V implica recorte.

![Modelo](../recursos/01.svg)

**Reto:** ¿Amplificar siempre mejora SNR?
