[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Por qué usar buffer entre etapas? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Aislamiento

Operacional alimentado tras RC puede reducir carga y establecer ganancia. Tiene límites de excursión, corriente y banda.

Pide un dibujo y explicación causal.

### Orden

Cada polo aporta −20 dB/década asintóticos. Dos RC aislados idénticos tienen −6 dB en fc individual, no −3. Butterworth segundo orden usa otra distribución de polos. Q controla amortiguamiento.

Pide un dibujo y explicación causal.

### Diseño

Define banda, atenuación y carga. Verifica GBW, slew rate, modo común, tolerancias y estabilidad. Barrido AC mide magnitud y fase; escalón revela asentamiento.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** Dos RC aislados fc=1 kHz: a 1 kHz magnitud conjunta=0,5; a 10 kHz≈0,0099.

**Práctica (30 min):** Simula dos RC 10 kΩ y 15,9 nF separados por seguidores; barre 100 Hz–10 kHz.

**Cierre (20 min):** ¿Por qué usar buffer entre etapas? Respuesta: Evita interacción de impedancias que cambia polos.
