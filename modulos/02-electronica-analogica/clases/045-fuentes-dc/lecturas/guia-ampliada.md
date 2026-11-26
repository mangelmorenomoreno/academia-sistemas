[← Clase](../README.md)

# Fuentes de alimentación DC de bajo voltaje

## Requisitos

Tensión, rango, corriente continua/pico, ondulación y conector. Corriente nominal es capacidad, no corriente impuesta. Solo fuentes comerciales aisladas de baja tensión, nunca abrir adaptadores.

## Protección

Limitar corriente, polaridad inversa y sobrevoltaje según riesgo. Condensador local suministra transitorios, no sustituye capacidad continua. Caída cable=IR; retorno compartido puede introducir ruido.

## Validación

Medir vacío y carga admisible, observar transitorios en simulación. Definir tolerancia antes de medir. No provocar cortocircuitos en fuente física.

## Ejemplo resuelto

3,3 V, 60 mA, cable 0,5 Ω: caída 0,03 V, tensión carga≈3,27 V.

![Modelo](../recursos/01.svg)

**Reto:** ¿Fuente de 1 A obliga a consumir 1 A?
