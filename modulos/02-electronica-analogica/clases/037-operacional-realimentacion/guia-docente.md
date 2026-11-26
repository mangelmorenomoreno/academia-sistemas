[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Cuándo falla V+≈V−? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Lazo abierto

Vout=Aol(V+−V−), limitado por alimentación. Ideal tiene ganancia infinita, entrada sin corriente y salida sin resistencia. Diferencia pequeña puede saturar salida.

Pide un dibujo y explicación causal.

### Realimentación

Devolver salida a inversora reduce error ante aumento de salida. En lazo negativo estable y región lineal V+≈V−; no son corto físico. Red fija ganancia cerrada.

Pide un dibujo y explicación causal.

### Límites

Revisar modo común, excursión, corriente, offset, ancho de banda, slew rate y estabilidad. Carga capacitiva puede introducir problemas de fase. No asumir entradas iguales en saturación.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** Aol=100000, seguidor: ganancia≈0,99999; entrada 1 V da error≈10 µV.

**Práctica (30 min):** Simula seguidor con alimentación compatible y carga 10 kΩ; varía entrada 0,5–2 V y compara lazo abierto.

**Cierre (20 min):** ¿Cuándo falla V+≈V−? Respuesta: Saturación, realimentación positiva, inestabilidad o límites reales.
