# Configuración SonarQube en Docker

Primer paso guardar en una carpeta deseada el archivo docker-compose.yml
Ejecutar el siguiente comando:

```
docker-compose up -d
```

Debemos descargar Sonar Scaner

https://docs.sonarsource.com/sonarqube/latest/analyzing-source-code/scanners/sonarscanner/

Al obtener la carpeta debemos descomprimir y dentro de la carpeta Bin pondremos nuestro poryecto para luego crear en la carpeta raiz de nuestro proyecto el archivo 
**sonar.project.properties**

Paso siguiente ir a nuestra web https://localhost:9000  para configurar un proyecto nuevo, todo eso lo muestro en el video de Youtube -> https://youtu.be/qbMCSIZULGA


