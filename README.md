# OPENJDK 8 CENTOS 7

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)


# Funcionalidades:

  - Permite definir la zona horaria al iniciar el servicio
  - Permite definir parametros de JAVA al iniciar el servicio

### Iniciar


Ejecutar para iniciar el servicio

```sh
$ docker run -d -e TIMEZONE=America/Montevideo -e JAVA_OPTS= sofislab/openjdk:jdk8-centos7
```
Eliga el tag según el sistema operativo deseado

### Variables


| Variable | Detalle |
| ------ | ------ |
| TIMEZONE | Define la zona horaria a utilizar (America/Montevideo, America/El_salvador) |
| JAVA_OPTS | Define parametros de la jvm |

License
----

Martin vilche
Sofis Solutions

