---
title: "Kata Markov Chain"
draft: false
date: "2017-05-17T12:46:00"
---

**About this Kata**

Build a text generator based on a Markov Chain.


[more detail on wikipedia](https://en.wikipedia.org/wiki/Markov_chain)

**En fraçais dans un premier temps**

Il faut faire un logiciel en deux partie.

Une première partie qui analyse un texte pour en extraire des statistiques. Chaque mot doit avoir la liste des mots possible suivant avec un pourcentage d'apparition. 

Par exemple avec ce texte :
```les hommes libres peuvent rester libres ou bien vendre leur liberté ```
Nous devrions extraire quelque chose qui dirait:
```
"Les" est suivi par "hommes" à 100%
"hommes" est suivi par "libres" à 100%
"libres" est suivi par "peuvent" à 50% et "ou" à 50%
...
```


Une deuxième partie qui génère un texte à partir des statistiques précédente et d'un paramètre sur le nombre de mot du texte à générer. On peut envisager d'avoir un autre paramètre sur le premier mot du texte.

