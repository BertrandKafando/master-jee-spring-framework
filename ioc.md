##  Inversion de controle

```
les frameworks s'occupe du code technique (performances, securité, transactions,..) et le dev s'occupe du code metier

>Spring 

>EJB + conteneur CDI


```

# utilité
```
+rapide + robuste

```

# comment ?

```
Il est possible grace à AOP : programation orienté aspect.

il permet de separer les différents aspect de l'app. le code de chaque partie (securité, accès db, Journalisation ..) dans une classe.

exemple: AspectJ, Spring AOP

c'est lui qui fait le greffage du code technique et le metier 


```
