# hum-tv

Reproductor de video de bienvenida del Launcher Motica Hum Living para las TV Samsung.

La app de Samsung abre su página desde dentro del paquete (`file://`) y desde ahí YouTube no reproduce: da el error 153 porque falta el encabezado Referer. Esta página se publica en https con GitHub Pages, pone el reproductor de YouTube y la app la maneja por `postMessage`.

- Página: https://adrianguzman85.github.io/hum-tv/video.html#v=<id de YouTube>
- No lleva datos de ninguna casa ni claves.
- Código fuente y documentación: repositorio `infraestructura`, carpeta `dispositivos/visor/hum` (archivo `reproductor/video.html`).
