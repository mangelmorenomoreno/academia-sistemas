[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Qué pasa al duplicar fs? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Conducción

En NMOS de lado bajo, fuente a referencia, drenador a carga. Pcond≈Irms²RDS(on). Con pulsos rectangulares, I²RDS(on)·D. Resistencia varía con temperatura y VGS.

Pide un dibujo y explicación causal.

### Conmutación

En flancos coinciden V e I. Psw≈½VDS·ID·(tr+tf)·fs para transiciones lineales. Driver carga puerta; potencia aproximada QgVdrive·fs.

Pide un dibujo y explicación causal.

### PWM

Carga resistiva ideal Vmedia=D·V; Pmedia=D·V²/R, no Vmedia²/R. Cargas reactivas requieren otro modelo y ruta de corriente.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** 5 V, 10 Ω, D=0,4, RDS(on)=0,1 Ω: I≈0,5 A, Pcond≈0,01 W y Pload ideal≈1 W.

**Práctica (30 min):** Simula 5 V, 100 Ω, PWM 1 kHz y D=25,50,75 %; mide media y RMS.

**Cierre (20 min):** ¿Qué pasa al duplicar fs? Respuesta: Psw se duplica aproximadamente si demás parámetros fijos.
