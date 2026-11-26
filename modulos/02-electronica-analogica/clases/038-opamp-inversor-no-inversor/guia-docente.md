[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Qué pasa si duplicas Rf en inversor? Pedir predicción antes de fórmulas.

**Desarrollo (45 min):**

### Inversor

V+ a referencia, V−≈V+ en región lineal. Kirchhoff con entrada ideal sin corriente: Vin/Rin≈−Vout/Rf respecto a referencia, Av=−Rf/Rin. Tierra virtual no es fuente arbitraria de corriente.

Pide un dibujo y explicación causal.

### No inversor

V− recibe divisor Vout·Rg/(Rg+Rf); igualando entradas Av=1+Rf/Rg. Alta impedancia; seguidor tiene ganancia uno.

Pide un dibujo y explicación causal.

### Diseño

Resistores bajos cargan salida y muy altos aumentan efectos de ruido y polarización. Revisar tolerancias, modo común, excursión y banda. Fuente simple puede exigir referencia intermedia.

Pide un dibujo y explicación causal.

**Ejemplo (15 min):** 10 kΩ y Rf=40 kΩ: inversor Av=−4, Vin=0,3 V relativa da −1,2 V relativa; no inversor Av=5.

**Práctica (30 min):** Simula ambas con ±5 V virtuales y 0,3 V pico; aumenta amplitud hasta recorte.

**Cierre (20 min):** ¿Qué pasa si duplicas Rf en inversor? Respuesta: Se duplica magnitud de ganancia si sigue lineal.
