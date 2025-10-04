# Celo---Chevalier-Dragon

0x9Da037841c0131ae0a9C402f0CAE5c7AF18d14a8

Caractéristiques du contrat :
Structures de données :

Chevalier : avec nom, points de vie, attaque, défense
Dragon : unique dans le jeu avec ses propres statistiques

Fonctions principales :

creerChevalier() - Chaque joueur peut créer son chevalier
attaquerDragon() - Lance une attaque qui calcule les dégâts et inclut une contre-attaque du dragon
soignerChevalier() - Restaure les PV à 100
ameliorerAttaque() / ameliorerDefense() - Améliore les stats du chevalier
ressusciterDragon() - Permet de recommencer le jeu

Mécanique de combat :

Les dégâts sont calculés selon : attaque - défense (minimum 1)
Le dragon contre-attaque automatiquement si il survit
Des événements sont émis pour suivre l'historique des combats

Le contrat ne gère aucun fonds (ETH ou tokens), c'est un jeu purement ludique basé sur la logique du smart contract !
