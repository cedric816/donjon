Le donjon diabolique ⚔️ 🛡
-------------------------
On va se créer un petit jeu minimaliste.

Le donjon, une page web hostile dans laquelle un joueur combat un terrible monstre. Qui sera le vainqueur ? Le joueur ? Le monstre ? Ou aucun des deux ? Lol.

Objectifs
---------
- Intégrer dans une page web sans aucun contenu un script client
- Développer & documenter le script client
- Déposer le code du projet sur un dépôt Git
- Publier le site sur un serveur web

Contexte
--------
Il est temps de se pencher sur du JavaScript en s'amusant à développer un jeu minimaliste.

Finalité pédagogique
--------------------
- Coder dans un langage de script client (JavaScript)
- Coder proprement, de manière facile à comprendre (pour les autres)
- Coder en commentant chaque nouvelle ligne

Compétence concernée
--------------------
- C3 : Développer une interface utilisateur web dynamique

Spécifications
--------------

### Fonctionnalités
- Au début du jeu, le joueur et le monstre possèdent chacun 20 points de vie.
- C'est le monstre qui attaque le joueur en premier
- Lorsque le monstre attaque le joueur, il occasionne au joueur des dégâts compris entre 1 et 6 points. On affiche une alerte résumant l'action, exemple : *Le monstre attaque. Il occasionne 5 point(s) de dégât(s). Le joueur n'a plus que 15 points de vie.*
- Lorsque le joueur attaque le monstre, il occasionne au monstre des dégâts compris entre 1 et 6 points. Idem, on affiche une alerte résumant l'action, exemple : *Le joueur attaque. Il occasionne 1 point(s) de dégât(s). Le monstre n'a plus que 19 points de vie.*
- Les combats entre le monstre et le joueur s'enchaînent jusqu'à ce que l'un des deux protagonistes n'ait plus de points de vie.
- Et on affiche le nom du perdant dans une alerte.

### Résultat attendu
- Le site n'a pas d'interface graphique, tout passe par des alertes JavaScript

## Livraison
- Déposer le code du projet sur un dépôt Git
- Publier une démo sur un serveur web

Envoyer un message à #front-end