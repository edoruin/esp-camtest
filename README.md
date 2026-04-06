# ESP Camera Test

Código para probar la cámara ESP32, basado en el repositorio oficial de Espressif, adaptado para conectar y probar con Arduino.

## Carpetas

### `cameraweb_Server/`
Versión adaptada con soporte MQTT. Publica la IP del servidor en HiveMQ Cloud para acceso remoto. Configurada para el modelo de cámara **AI-THINKER**.

### `Sketch_06.1_CameraWebServer/`
Versión base del código original (Freenove). Versión simple del servidor web para pruebas iniciales de la cámara.

## Uso

1. Seleccionar el modelo de cámara en `board_config.h` o en el archivo `.ino`
2. Configurar credenciales WiFi
3. Compilar y cargar en el ESP32
4. Acceder vía web a la IP asignada

## Requisitos

- ESP32 con cámara
- Biblioteca `esp-camera`
- WiFi disponibles
