# SOUVENIRS

Projet du M2 MIAGE - Université de Bordeaux

## Getting Started

Pour ce projet nous utilisons Spring Boot/ReactJS avec Docker

### Prerequisites

Vous devez posséder docker, il faut ensuite ce placer dans le dossier souvenirs et executer le Dockerfile comme suit:

```
docker build -t springio .
```

### Installing

Après avoir construit l'image, on lance maven avec cette commande :

```
mvnw clean install dockerfile:build 

```



On lance ensuite nos containeurs :
```
docker-compose up
```
## Built With

* [Docker](https://www.docker.com/) - Docker plateform
* [Maven](https://maven.apache.org/) - Dependency Management
* [ReactJS](https://reactjs.org/) - A Javascript library for building user interfaces

## Authors

* Jean Arhancetebehere 
