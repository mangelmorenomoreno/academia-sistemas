[← Clase](../README.md)

# Amplificador inversor y no inversor

## Inversor

V+ a referencia, V−≈V+ en región lineal. Kirchhoff con entrada ideal sin corriente: Vin/Rin≈−Vout/Rf respecto a referencia, Av=−Rf/Rin. Tierra virtual no es fuente arbitraria de corriente.

## No inversor

V− recibe divisor Vout·Rg/(Rg+Rf); igualando entradas Av=1+Rf/Rg. Alta impedancia; seguidor tiene ganancia uno.

## Diseño

Resistores bajos cargan salida y muy altos aumentan efectos de ruido y polarización. Revisar tolerancias, modo común, excursión y banda. Fuente simple puede exigir referencia intermedia.

## Ejemplo resuelto

10 kΩ y Rf=40 kΩ: inversor Av=−4, Vin=0,3 V relativa da −1,2 V relativa; no inversor Av=5.

![Modelo](../recursos/01.svg)

**Reto:** ¿Qué pasa si duplicas Rf en inversor?
