[← Clase](../README.md)

# Diodos Zener y regulación

## Ruptura

Zener diseñado para ruptura inversa permite corriente cerca de Vz mediante túnel o avalancha. Requiere limitar corriente. Tensión depende de corriente y temperatura; Pz=VzIz.

## Regulación

Rs en serie y Zener paralelo: Is=(Vin−Vz)/Rs e Iz=Is−IL. Si Iz cae por debajo de rango de regulación, salida baja. Sin carga Iz crece.

## Potencia

Evalúa entrada máxima y carga mínima; PR=Is²Rs y Pz=VzIz. Regulación paralelo disipa energía a carga pequeña y no sirve para toda potencia.

## Ejemplo resuelto

9 V, 5,1 V, 390 Ω: Is=10 mA. IL=4 mA da Iz=6 mA y Pz=30,6 mW.

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué no eliminar Rs?
