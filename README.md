# Docker multi-stage build

En este simple repositorio se puede observar un ejemplo de una imagen multi-stage. 

En este caso nos beneficiamos de unificar el Dockerfile de producción y desarrollo en uno solo.

Por otro lado, la imágen final de producción optimiza el tamaño final.

## Aclaración sobre el código
Este código es simplemente una app generada con create-react-app. Para correrla en producción simplemente hacemos un build y luego utilizamos el código dentro de `build`.