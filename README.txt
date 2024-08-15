# Keylogger para Linux

Este proyecto es una implementación básica de un keylogger para sistemas Linux. El código en C captura las entradas del teclado y las guarda en un archivo de registro.

## Descripción

El keylogger lee eventos de teclado desde el dispositivo `/dev/input/event0` y convierte los códigos de las teclas en caracteres ASCII, que luego se almacenan en `keylogger.txt`.

## Requisitos

- Sistema Linux
- Compilador de C (por ejemplo, `gcc`)
- Permisos para acceder a `/dev/input/event0`

## Instrucciones de Uso

1. **Compilar el código**:
   ```bash
   gcc -o keylogger keylogger.c
