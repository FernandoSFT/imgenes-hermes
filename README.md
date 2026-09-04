# Imágenes Hermes · SAFE TOUR

Repositorio público de recursos visuales creados por el perfil Hermes `fotografo`.

## Estructura

- `assets/YYYY/MM/`: imágenes finales publicables.
- `previews/YYYY/MM/`: páginas HTML de previsualización social.
- `manifests/index.json`: catálogo técnico sin datos privados.

## URL directa de una imagen

```text
https://raw.githubusercontent.com/FernandoSFT/imgenes-hermes/main/assets/YYYY/MM/archivo.jpg
```

## Reglas de publicación

- Solo se publican imágenes que hayan superado validación técnica y visual.
- No se almacenan claves, prompts completos, nombres de clientes ni datos internos.
- Los archivos se entregan sin EXIF ni metadatos privados.
- Cada imagen usa un nombre ASCII descriptivo, dimensiones y checksum SHA-256.
- MiniMax se invoca exclusivamente mediante `image-01`, sin fallback; el resultado se descarga inmediatamente antes de publicarse.

## Uso

Las URL directas sirven para web y como origen de descarga para automatizaciones. Las redes sociales deben subir el archivo mediante su API o interfaz para que quede alojado en su propia CDN.
