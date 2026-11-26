[← Clase](README.md)

# Guía docente

**Inicio (10 min):** ¿Por qué una bobina se opone a cambios de corriente, no a toda corriente? Pedir una predicción y recuperar conservación de carga y energía.

**Desarrollo (45–60 min):**

### De la corriente al campo magnético

La corriente produce campo magnético alrededor del conductor. Las espiras de una bobina hacen que gran parte de sus campos contribuyan al flujo enlazado. Un núcleo de permeabilidad elevada puede aumentar el flujo para una corriente dada. En régimen lineal el flujo enlazado λ=Li. La inductancia L se mide en henrios: 1 H=1 V·s/A. Faraday y Lenz explican por qué un cambio de flujo induce una tensión cuyo efecto se opone a la variación. Con convenio pasivo vL=L·di/dt. Una corriente constante no genera tensión inductiva ideal.

Pedir al estudiante: Dibuja espiras y el campo dentro de la bobina. Señala qué sucede cuando aumenta i.

### Transitorio RL paso a paso

Kirchhoff en una rama serie da V=Ri+L·di/dt. Si inicialmente i=0, la solución es i(t)=V/R·(1−e^(−tR/L)). τ=L/R en segundos. En el instante inicial la corriente no ha aumentado y casi todo V aparece en L; al final i≈V/R y vL≈0. Durante una descarga con trayectoria cerrada, i=I0e^(−tR/L). Una tensión finita no produce un salto instantáneo de corriente, de forma análoga a la continuidad del voltaje en C.

Pedir al estudiante: Compara i(t) en RL con Vc(t) en RC. Identifica qué magnitud no puede cambiar abruptamente.

### Energía, saturación y protección

La energía magnética E=½LI² se deduce integrando potencia p=vi=L·i·di/dt. Una interrupción rápida de corriente puede generar tensión elevada: la energía debe salir hacia alguna trayectoria. En relés DC se utiliza una ruta de rueda libre correctamente orientada. El cobre real tiene resistencia y disipa calor. Un núcleo puede saturarse a corriente alta y reducir su inductancia efectiva, acelerando el crecimiento de corriente.

Pedir al estudiante: Explica por qué no debe abrirse una bobina energizada sin una ruta de corriente prevista.

**Ejemplo (15 min):** V=5 V, R=100 Ω, L=0,1 H: τ=0,1/100=0,001 s. I∞=5/100=0,05 A. I(τ)=0,05(1−e⁻¹)=31,6 mA; vL(τ)=5e⁻¹=1,84 V. E∞=½·0,1·0,05²=0,000125 J.

**Laboratorio (30 min):** Simula 5 V, R=100 Ω y L=100 mH. Grafica i y vL con paso de tiempo inferior a 0,1 ms. Registra a 0, 1 y 5 ms; repite con L=200 mH. Proporciona una ruta de descarga antes de abrir el interruptor virtual.

**Cierre (20 min):** pedir respuestas individuales, después retroalimentar con el solucionario. No evaluar solo memorización de fórmulas.
