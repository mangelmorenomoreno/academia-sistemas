[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Vout=D·Vin vale para cualquier convertidor? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Lineal

Elemento de paso bajo realimentación. Pérdida≈(Vin−Vout)Iout más consumo propio. Eficiencia aproximada Vout/Vin. Dropout es margen de entrada para regulación.

Pide un dibujo y explicación causal.

### Buck

Alterna interruptor y trayectoria de corriente del inductor; condensador filtra. Ideal en conducción continua Vout≈D·Vin por balance volt-segundos. Boost tiene otra relación.

Pide un dibujo y explicación causal.

### Selección

η=Pout/Pin. Pérdidas conmutadas en conducción, flancos, núcleo y control; ondulación y EMI dependen de diseño. Lineal puede convenir con poco diferencial o exigencia de ruido.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** 9 V a 3,3 V a 100 mA: Pout=0,33 W; lineal pierde≈0,57 W; buck hipotético 85 % pierde≈0,058 W.

**Práctica (30 min):** Compara modelos virtuales lineal y buck con carga 33 Ω; calcula pérdidas.

**Cierre (20 min):** ¿Vout=D·Vin vale para cualquier convertidor? Respuesta: No, corresponde a buck ideal en conducción continua.
