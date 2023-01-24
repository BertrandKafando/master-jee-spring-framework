## HTTP Hypertext Transfert Protocol 
```
c'est un protocole qui permet de communiquer avec le serveur

> recuperer des documents à partir d'un server : statique( img, pdf) dynamique(php,jsp,..) 

> soumission des formulaires

```

# Fonctionnement

```
> half duplex (dans ce mode le serveur ne peut envoyé de requete) http.0
1-Le client se connecte au serveur (Créer un socket )
2-Le client envoie la requete (demande de document): HTTP
3- Le serveur cherche le doc et renvoie la réponse (le doc code=200 ou erreur 400)

> duplex websocket
il faut utiliser websocket
1-Le client se connecte au serveur (Créer un socket )
2-le serveur lui renvoie aussi du javascript qui etablie une connection permanente


```


# Notions de bases

```
> Un serveur: ce n'est pas une machine c'est application  . Dans une machine on peut demarrer +sieurs machines. Une application qui demarre un objet de type ServerSocket qui ouvre un service d'écoute pour qu'un client se connecte.
Il s'identifie à travers le numero de port.



> C'est quoi se connecter ? Le client cree une socket (contient add IP Serveur +port)  et envoie une demande au serveur qui crée à son tour une socket (contient add IP Client +port)  pour autoriser la connexion .




```


# Les méthodes HTTP

```

```

# Les codes des réponses HTTP

```

```


