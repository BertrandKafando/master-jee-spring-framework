## Injection de dependance


```


```

# types


```
> statique  getters

> dynamique avec un  fichier de configuration

> framework spring, cdi pour un serveur d'App comme ejb

```

# solution du framework spring


```

> fichier xml +setter || +constructeur


> Annotations

Lorque qu'il y'a plusieurs implementation ,il faut donner un nom à chaque component .
Dans ce cas on doit utiliser @qualifer("nom du component à instancier") pour choisir 
version bd

>contructeurs

il choisit le premier


```

# Annontations

```
@ component -> generale

dao -> @repository
metier -> @service
web -> @controller

```
