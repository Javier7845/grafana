# Automatizacion de Grafana y Mysql en Docker y Vagrant
## Overview
Este proyecto plantea automatizar los servicios de Mysql y Grafana utilizando como entorno de virtualizacion Docker y Vagrant. La base de datos a visualizar esta incluida en la carpeta "database"
## Requirements
- Docker
- Vagrant
## Docker
1. Clone or download this repository in the home directory.
```
git clone https://github.com/Javier7845/grafana
```
2. Dentro de la carpeta del repositorio descargado corremos el siguiente comando para levantar los servicios
```
docker-compose up -d
```
## Vagrant
1. Clone or download this repository in the home directory.
```
git clone https://github.com/Javier7845/grafana
```
2. Dentro de la carpeta del repositorio descargado corremos el siguiente comando para levantar los servicios
```
vagrant up
```
## Usage
Asegurate de que los contenedores con los servicios esten corriendo
```
docker container ls -a
```
Ahora escribe en tu navegador.
```
localhost:3000
```
## Authors of this project
- Javier - [LinkedIn](https://www.linkedin.com/in/javec/)
- Jaime - [LinkedIn](https://www.linkedin.com/in/jaime-astudillo-664754228/)
