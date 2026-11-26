[← Clase](../README.md)

# Diagnóstico analógico y simulación

## Modelo

Identifica fuente, referencia, entrada, transferencia y salida. Calcula valores esperados y tolerancias. Divide bloques y busca primero fuera de rango; simulación no garantiza montaje.

## Hipótesis

Si salida satura, revisar alimentación, modo común, signo de realimentación y entrada. Si hay ruido, revisar retorno, desacoplo, interferencia y banda. Cambia variable por vez.

## Confirmación

Inspecciona continuidad sin energía. Solo energiza con fuente limitada segura. Revisa DC, luego señal y carga; repite pruebas al corregir. Documenta causa raíz y prevención.

## Ejemplo resuelto

No inversor Av=3, entrada 0,4 V relativa: salida 1,2 V. Si mide 0,4 V, verificar Rf en corto (seguidor).

![Modelo](../recursos/01.svg)

**Reto:** ¿Por qué no basta simulación exitosa?
