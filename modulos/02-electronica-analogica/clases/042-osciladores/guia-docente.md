[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Qué cambia al duplicar C? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Arranque

Oscilador convierte energía DC en señal variable. Condición inicial o ruido inicia cambio. Lazo sinusoidal lineal sostenido: fase 0° módulo 360° y magnitud cercana a uno. Arranque exige crecimiento; no linealidad limita amplitud.

Pide un dibujo y explicación causal.

### Relajación

Schmitt y RC cargan y descargan entre umbrales. Salida ±Vs y umbrales ±βVs: T=2RC·ln((1+β)/(1−β)). Salida cuadrada, Vc exponencial por tramos.

Pide un dibujo y explicación causal.

### Estabilidad

Tolerancia, temperatura, ruido y retardo alteran frecuencia. Cristal aprovecha resonancia mecánica. Distingue periodo, frecuencia, ciclo útil y jitter.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** 10 kΩ, 100 nF, β=1/3: T≈1,386 ms y f≈721 Hz.

**Práctica (30 min):** Simula Schmitt RC con ±5 V virtuales; añade condición inicial pequeña si no arranca; mide cinco periodos.

**Cierre (20 min):** ¿Qué cambia al duplicar C? Respuesta: Frecuencia se reduce aproximadamente a mitad.
