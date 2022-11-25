# Proyecto-Final-De-Ingenieria-De-Software

## Integrantes

🔷 *Miguel Angel Deza Cuela
🔷 *Alvaro Ticona Motta
🔷 *Cecilia del Pilar Vilca Alvites
🔷 *Joao Franco Emanuel Chávez Salas
🔷 *Ancel Alain F. Cruz Chaiña


## Pipeline

### Fases:
#### BUILD
Se usó COMPOSER para la construcción automática del proyecto, su archivo de configuración correspondiente es el composer.json

#### ANALYSIS
Se usó la herramienta SONARQUBE para el análisis estático del codigo, su archivo de configuración correspondiente es el sonar-project.properties y almacena los resultados en la carpeta .scannerwork

#### UNIT TEST
Se usó el framework PHPUNIT para las pruebas unitarias de los bloques de codigo, un archivo .php para cada prueba y un archivo tester.py  para el almacenamiento de los resultados de todos las pruebas en un archivo results.txt

#### PERFORMANCE TEST
Se usó la herramienta  JMeter para poner a prueba el desenvolvimiento de la aplicación web en diversas situaciones, el archivo de configuración es un archivo .jmx y los resultados se almacenan en un archivo .jtl

#### DEPLOYMENT
Se usó la herramienta NcFTP con protocolo FTP para el despliegue de aplicaciones web en los servidores. Se ejecutaron comandos en lenguaje Batch para desplegar cada uno de las subcarpetas y archivos del proyecto.
