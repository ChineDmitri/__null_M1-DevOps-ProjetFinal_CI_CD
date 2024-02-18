#### Création d'un image pour dev local : 

```bash
docker build -t bdd:dev -f Dockerfile.bdd .
```


#### Lencement conteneur depuis image Mysql pour dev :

```bash
docker container run --name=mysql-dev -p 3310:3306 bdd:dev
```


#### Arrêter/Démarrer/Redémarrer  containeur Mysql :

```bash
docker stop mysql-dev
```

```bash
docker start mysql-dev
```

```bash
docker restart mysql-dev
```

