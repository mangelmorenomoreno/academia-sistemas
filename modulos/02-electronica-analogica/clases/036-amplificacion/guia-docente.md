[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Amplificar siempre mejora SNR? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Ganancia

Av=Vout/Vin, Ai=Iout/Iin, Ap=Pout/Pin. Tensión en dB=20log10 de magnitud de Av, potencia=10log10 Ap. Energía adicional proviene de fuente.

Pide un dibujo y explicación causal.

### Límites

Alimentación y corriente limitan excursión. Polos reducen ganancia y añaden fase a altas f; slew rate limita rapidez de salida incluso dentro de banda de pequeña señal.

Pide un dibujo y explicación causal.

### Ruido

Fluctuación no deseada, distinta de distorsión no lineal. SNR=10log10(Pseñal/Pruido). Amplificar también amplifica ruido y añade propio; reducir banda innecesaria disminuye ruido integrado.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** 0,1 V pico, Av=20: salida ideal 2 V pico, 26 dB. Límite ±1,5 V implica recorte.

**Práctica (30 min):** Simula ganancia 10 con límite ±2 V y señales 0,1 y 0,4 V pico; añade perturbación de 10 mV.

**Cierre (20 min):** ¿Amplificar siempre mejora SNR? Respuesta: No; amplifica ruido existente y añade propio.
