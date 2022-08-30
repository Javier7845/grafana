# Automatizacion de Grafana y MySQL en Docker y Vagrant
## Overview
Este proyecto plantea automatizar los servicios de MySQL y Grafana utilizando como entorno de virtualizacion Docker y Vagrant. La base de datos a visualizar esta incluida en la carpeta "database".
## Requirements
- Docker
- Vagrant
## Docker
1. Clone or download this repository in the home directory.
```
git clone https://github.com/Javier7845/grafana.git
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
2. Descomprimimos el archivo y entramos a la carpeta.
```
cd /grafana-main
```
2. Desde la terminal escribimos el siguiente comando para levantar la maquina virtual.
```
vagrant up
```
## Usage
1. Asegurate de que los contenedores con los servicios esten corriendo
```
docker container ls -a
```
2. Ahora escribe en tu navegador.
```
localhost:3000
```
## Authors of this project
- Javier - [LinkedIn](https://www.linkedin.com/in/javec/)
- Jaime - [LinkedIn](https://www.linkedin.com/in/jaime-astudillo-664754228/)
