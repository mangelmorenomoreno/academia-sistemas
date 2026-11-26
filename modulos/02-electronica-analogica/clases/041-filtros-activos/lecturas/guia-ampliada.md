[← Clase](../README.md)

# Filtros activos y respuesta en frecuencia

## Aislamiento

Operacional alimentado tras RC puede reducir carga y establecer ganancia. Tiene límites de excursión, corriente y banda.

## Orden

Cada polo aporta −20 dB/década asintóticos. Dos RC aislados idénticos tienen −6 dB en fc individual, no −3. Butterworth segundo orden usa otra distribución de polos. Q controla amortiguamiento.

## Diseño

Define banda, atenuación y carga. Verifica GBW, slew rate, modo común, tolerancias y estabilidad. Barrido AC mide magnitud y fase; escalón revela asentamiento.

## Ejemplo resuelto

Dos RC aislados fc=1 kHz: a 1 kHz magnitud conjunta=0,5; a 10 kHz≈0,0099.

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué usar buffer entre etapas?
