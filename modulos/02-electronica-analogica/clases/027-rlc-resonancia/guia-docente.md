[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Por qué un circuito responde más intensamente a determinada frecuencia? Pedir una predicción y recuperar conservación de carga y energía.

**Desarrollo (45–60 min):**

### Impedancia y fase

En régimen senoidal, una resistencia tiene ZR=R; una bobina ideal ZL=jωL y un condensador ZC=1/(jωC)=−j/(ωC), con ω=2πf. La unidad de impedancia es Ω. En serie Z=R+j(ωL−1/ωC); su módulo es √(R²+(ωL−1/ωC)²). En L, el voltaje adelanta a la corriente 90°; en C, atrasa 90°. Se suman fasores, no solo magnitudes. A frecuencia baja domina la reactancia de C; alta, la de L.

Pedir al estudiante: Dibuja VR, VL y VC como flechas perpendiculares y muestra su suma.

### Intercambio de energía y resonancia

La energía eléctrica de C y la magnética de L pueden intercambiarse. En RLC serie, a ω0=1/√(LC) se cancelan las reactancias. f0=ω0/(2π), la impedancia queda R y la corriente eficaz es máxima para fuente de amplitud constante. Las tensiones individuales de L y C pueden ser mayores que la tensión de fuente y se cancelan fasorialmente. La resistencia disipa energía y la fuente la repone: no hay creación de energía.

Pedir al estudiante: Predice la corriente a frecuencia inferior, igual y superior a f0.

### Amortiguamiento y selectividad

Para RLC serie ideal, Q=ω0L/R y el ancho de banda de media potencia Δf=R/(2πL). Al aumentar R, el pico de corriente disminuye y la curva se ensancha. Sin fuente, la energía se disipa en R; según amortiguamiento, pueden ocurrir oscilaciones decrecientes. En un circuito paralelo el comportamiento de impedancia es distinto; no trasladar reglas de serie sin derivarlas.

Pedir al estudiante: Compara curvas de corriente para dos resistencias diferentes.

**Ejemplo (15 min):** L=10 mH=0,01 H, C=1 µF=10⁻⁶ F, R=100 Ω: f0=1/(2π√(0,01·10⁻⁶))≈1592 Hz. Con 1 V RMS a resonancia I=1/100=10 mA. Q≈1. Δf≈1592 Hz. Si C se cuadruplica, f0≈796 Hz.

**Laboratorio (30 min):** Simula una fuente senoidal de 1 V RMS con R=100 Ω, L=10 mH, C=1 µF en serie. Barre 500–5000 Hz, registra corriente eficaz y fase. Repite R=200 Ω; compara pico y ancho de banda.

**Cierre (20 min):** pedir respuestas individuales, después retroalimentar con el solucionario. No evaluar solo memorización de fórmulas.
