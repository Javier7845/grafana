# Automatizacion de Grafana y MySQL en Docker y Vagrant
## Overview
Este proyecto plantea automatizar los servicios de MySQL y Grafana utilizando como entorno de virtualizacion Docker y Vagrant. La base de datos a visualizar esta incluida en la carpeta "database".
## Requirements
- Docker
- Vagrant
## Docker
1. Clone or download this repository in the home directory:
```
git clone https://github.com/Javier7845/grafana.git
```
2. Descompre el archivo y entra a la carpeta:
```
cd /grafana-main
```
3. Dentro de la carpeta escribe el siguiente comando para levantar los servicios:
```
docker-compose up -d
```
## Vagrant
1. Clone or download this repository in the home directory:
```
git clone https://github.com/Javier7845/grafana
```
2. Descompre el archivo y entra a la carpeta:

2. Dentro de la carpeta escribimos el siguiente comando para levantar la maquina virtual con los servicios:
```
vagrant up
```
4. Luego escribimos:
```
vagrant ssh
```
# Usage
## Docker
1. Asegurate de que los contenedores con los servicios esten corriendo:
```
docker ps
```
2. Ahora escribe en tu navegador:
```
localhost:3000
```
## Vagrant
1. Asegurate de que los contenedores con los servicios esten corriendo dentro de la maquina virtual:
```
docker ps
```
2. Ahora escribe en tu navegador:
```
192.168.56.107:3000
```
## Authors of this project
- Javier - [LinkedIn](https://www.linkedin.com/in/javec/)
- Jaime - [LinkedIn](https://www.linkedin.com/in/jaime-astudillo-664754228/)
