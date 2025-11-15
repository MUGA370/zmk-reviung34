# ZMK Firmware para teclado de 34 teclas

## Descripción
Teclado de 34 teclas con 2 capas y tira LED WS2812B.  
Basado en la **Pro Micro SuperMini nRF52840 USB-C Nano** con soporte para Bluetooth, Zigbee y 2.4GHz.

## Especificaciones
- **Filas**: 4 (10, 10, 9, 5)
- **Columnas**: 10
- **Matriz**: 4x10
- **LEDs**: WS2812B (10 LEDs)
- **Controlador**: nRF52840

## Pines usados

| Función | Pin GPIO |
|---------|----------|
| Row 0   | P0.04    |
| Row 1   | P0.08    |
| Row 2   | P0.09    |
| Row 3   | P0.03    |
| Col 0   | P0.06    |
| Col 1   | P0.07    |
| Col 2   | P0.05    |
| Col 3   | P0.10    |
| Col 4   | P0.16    |
| Col 5   | P0.14    |
| Col 6   | P0.15    |
| Col 7   | P0.18    |
| Col 8   | P0.19    |
| Col 9   | P0.20    |

## Instalación

1. Clona este repositorio.
2. Sigue la guía oficial de ZMK para compilar: https://zmk.dev/docs
3. Flashea el archivo `.uf2` generado en tu placa.
