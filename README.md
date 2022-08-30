# Automatizacion de Grafana y MySQL en Docker y Vagrant
## Overview
Este proyecto plantea automatizar los servicios de MySQL y Grafana utilizando como entorno de virtualizacion Docker y Vagrant. La base de datos a visualizar esta incluida en la carpeta "database".
## Requirements
- Docker
- Docker-compose
- Vagrant
## Docker
1. Clone or download this repository:
```
git clone https://github.com/Javier7845/grafana.git
```
2. Entra a la carpeta del repositorio:
```
cd /grafana
```
3. Dentro de la carpeta escribe el siguiente comando para levantar los servicios:
```
sudo docker-compose up -d
```
## Vagrant
1. Clone or download this repository:
```
git clone https://github.com/Javier7845/grafana
```
2. Entra a la carpeta del repositorio:
```
cd /grafana
```
2. Dentro de la carpeta escribimos el siguiente comando para levantar la maquina virtual con los servicios:
```
vagrant up
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
vagrant ssh
```
```
docker ps
```
2. Ahora escribe en tu navegador:
```
192.168.56.107:3000
```

## Install docker-compose
```
sudo apt-get -y update
sudo apt-get install -y docker-ce docker-ce-cli containerd.io docker-compose-plugin
sudo apt-get -y updated
sudo apt-get install -y docker-compose
```
## Authors of this project
- Javier - [LinkedIn](https://www.linkedin.com/in/javec/)
- Jaime - [LinkedIn](https://www.linkedin.com/in/jaime-astudillo-664754228/)
