# Crispulo Reporter — IPTV Live Channel

Proyecto independiente para convertir una transmisión autorizada de **Crispulo Reporter** en una fuente de canal IPTV estable.

## Objetivo

```text
YouTube Live
    ↓
Detector de estado
    ↓
Extractor / relay
    ↓
HLS
    ↓
Endpoint de canal estable
    ↓
M3U / IPTV
```

## Fuente de prueba

- Nombre: Crispulo Reporter
- YouTube Live: `JvYw0HlgceM`
- Uso: prueba autorizada por el responsable de la transmisión

## Importante

Este repositorio no contiene credenciales ni claves privadas. Los secretos y configuraciones sensibles deberán manejarse mediante variables de entorno o GitHub Actions Secrets.

GitHub Actions se utilizará para validación, automatización y despliegue; el relay de vídeo 24/7 deberá ejecutarse en un servidor persistente/VPS, no en un runner efímero de GitHub Actions.

## Estado

🚧 Prototipo inicial.
