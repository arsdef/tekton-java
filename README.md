# tekton-java
Este pipeline detecta automáticamente cambios en un repositorio Git mediante un webhook, clona el código, lo compila, ejecuta pruebas unitarias, pasa SonarQube, construye el contenedor con Buildah, analiza la imagen con Tryvi, sube la imagen al registro, actualiza un chart de Helm y ejecuta pruebas de integración con Kubetest2.
