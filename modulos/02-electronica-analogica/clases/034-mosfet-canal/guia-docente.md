[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Por qué no basta Vth? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Estructura

Puerta aislada controla electrostáticamente superficie entre fuente y drenador. VGS suficiente crea canal de inversión NMOS. Corriente DC de puerta ideal nula; capacitancia exige carga al conmutar.

Pide un dibujo y explicación causal.

### Regiones

En modelo largo ideal, VGS por debajo Vth corte aproximado. Por encima, VDS menor que VGS−Vth es lineal; mayor es saturación de corriente. Interruptor encendido busca baja RDS(on) en lineal.

Pide un dibujo y explicación causal.

### Protección

Óxido sensible a ESD. Pulldown evita puerta flotante; respetar VGS máximo. Vth no garantiza RDS(on) baja; verificar hoja de datos al voltaje real.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** 0,08 Ω a VGS=4,5 V e ID=0,5 A: VDS=0,04 V y P=0,02 W.

**Práctica (30 min):** Simula NMOS con 5 V y carga 100 Ω, barre VGS 0–5 V; añade pulldown 100 kΩ.

**Cierre (20 min):** ¿Por qué no basta Vth? Respuesta: Se especifica con corriente pequeña, no asegura baja resistencia con carga.
