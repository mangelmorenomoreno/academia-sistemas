[← Clase](../README.md)

# Filtros RC pasivos y frecuencia de corte

## Pasa-bajos

R serie y C a referencia, salida sobre C. H=1/(1+jωRC); magnitud=1/√(1+(ωRC)²). F baja: reactancia C alta; f alta: desvía señal. Fase −atan(ωRC).

## Pasa-altos

C serie y R a referencia, salida sobre R. H=jωRC/(1+jωRC). DC estable bloqueada idealmente, altas f pasan; no hay electrones cruzando dieléctrico.

## Corte

fc=1/(2πRC). Magnitud en fc 0,707 o −3,01 dB. Pendiente asintótica 20 dB/década. Carga y resistencia fuente alteran ganancia y corte.

## Ejemplo resuelto

10 kΩ, 100 nF: fc≈159 Hz. A fc, 1 V pico da 0,707 V; a 1590 Hz≈0,0995 V en pasa-bajos.

![Modelo](../recursos/01.svg)

**Reto:** ¿Elimina todas las frecuencias mayores a fc?
