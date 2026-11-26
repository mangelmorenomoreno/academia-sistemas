[← Clase](../README.md)

# MOSFET: canal, umbral, regiones y protección ESD

## Estructura

Puerta aislada controla electrostáticamente superficie entre fuente y drenador. VGS suficiente crea canal de inversión NMOS. Corriente DC de puerta ideal nula; capacitancia exige carga al conmutar.

## Regiones

En modelo largo ideal, VGS por debajo Vth corte aproximado. Por encima, VDS menor que VGS−Vth es lineal; mayor es saturación de corriente. Interruptor encendido busca baja RDS(on) en lineal.

## Protección

Óxido sensible a ESD. Pulldown evita puerta flotante; respetar VGS máximo. Vth no garantiza RDS(on) baja; verificar hoja de datos al voltaje real.

## Ejemplo resuelto

0,08 Ω a VGS=4,5 V e ID=0,5 A: VDS=0,04 V y P=0,02 W.

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué no basta Vth?
