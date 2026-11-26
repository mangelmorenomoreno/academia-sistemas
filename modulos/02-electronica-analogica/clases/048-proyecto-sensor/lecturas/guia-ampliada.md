[← Clase](../README.md)

# Proyecto: sensor con acondicionamiento

## Requisitos

Sensor resistivo virtual 5–20 kΩ y 3,3 V. Define rango de salida, error aceptable y respuesta. Dibuja divisor, buffer, filtro y ADC ideal. Calcula extremos.

## Diseño

R fijo 10 kΩ arriba y sensor abajo: salida 1,10–2,20 V. Filtro tras buffer 10 kΩ, 1 µF: fc≈15,9 Hz, τ=10 ms. ADC 10 bits con floor: códigos 341–682.

## Validación

Entrega esquema, ecuaciones, medidas, incertidumbre, prueba de ruido y falla virtual. Justifica no linealidad de divisor y respuesta temporal. Calibrar para inferir magnitud física real.

## Ejemplo resuelto

Rs=20 kΩ: 3,3×20/30=2,2 V; código floor(2,2/3,3×1024)=682; filtro alcanza 63,2 % del cambio a 10 ms.

![Modelo](../recursos/01.svg)

**Reto:** ¿Qué cambia al duplicar C?
