[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Por qué un cambio pequeño puede no cambiar código? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Transducción

LDR cambia resistencia con luz, NTC con temperatura. Otros sensores entregan corriente o tensión. Sensibilidad, resolución, exactitud y precisión difieren; calibración usa referencias conocidas.

Pide un dibujo y explicación causal.

### Divisor

R fijo arriba y Rs abajo: Vout=VccRs/(R+Rs). NTC abajo disminuye Vout al calentar; relación no lineal e impedancia R paralelo Rs puede requerir buffer.

Pide un dibujo y explicación causal.

### ADC

Filtro reduce ruido y limita banda. ADC N bits: paso nominal Vref/2^N. Nyquist exige muestreo mayor que doble máxima frecuencia de señal limitada en banda; dejar margen para filtro real.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** 3,3 V, R=10 kΩ: Rs=10 kΩ da 1,65 V; 5 kΩ da 1,10 V. ADC 10 bits: paso≈3,22 mV.

**Práctica (30 min):** Simula Rs=5,10,20 kΩ; calcula códigos floor(Vout/3,3×1024), limitados a 0–1023.

**Cierre (20 min):** ¿Por qué un cambio pequeño puede no cambiar código? Respuesta: Cuantización finita y ruido.
