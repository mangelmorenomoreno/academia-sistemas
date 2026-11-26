[← Clase](../README.md)

# BJT como interruptor y amplificador

## Interruptor

Se busca saturación con margen según hoja de datos y β forzado. RB≈(Vcontrol−VBE)/IB. P≈VCE(sat)IC. Carga inductiva requiere protección.

## Amplificación

En activa alrededor de Q, pequeñas variaciones de entrada cambian IC. Emisor común con emisor AC a referencia: Av≈−gmRCef y gm≈IC/VT. Signo indica inversión.

## Recorte

Corte y saturación impiden proporcionalidad. Escoger Q con margen; resistencia de emisor sin desacoplar reduce ganancia y mejora estabilidad. La fuente entrega energía.

## Ejemplo resuelto

Control 3,3 V, carga 10 mA, β forzado 10: IB=1 mA, RB≈2,5 kΩ con VBE≈0,8 V.

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué no amplificar en saturación?
