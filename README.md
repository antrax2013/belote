# Kata - Belote

La belote est un jeu de cartes où 2 équipes s'affrontent. Il se joue avec un jeu de 32 cartes. 

A chaque début de tour, est désignée une famille de cartes, qui sera l'atout pour toute la durée du tour. La valeur et l'ordre des cartes de cette famille est alors modifée.

## Les points à la belote

| Valeurs     | 20| 14| 11 | 10 | 4 | 3 |	2 |	0 |	0 |	0 |
|--           |-- |-- |--  |--  |-- |-- |-- |-- |-- |-- |
| Hors atout  |  |   | A | 10 |	R | D | V | 9 | 8 |	7 |
| À l'atout   | V | 9 | A | 10 | R | D |  |  | 8 | 7 |


### Cas particuliers (Bonus)
#### Belote et Rebelote
Il y a belote et rebelote quand les joueurs d'une même équipe annoncent belote et rebelote au moment où ils les jouent le roi et la dame d'atout. 

Dans ce cas l'équipe engrange __20pts__ supplémentaires.

Dans notre cas de figure, les joueurs sont expérimentés et l'annoncent systématiquement (l'ordre n'a pas d'importance).

#### Le 10 de der
L'équipe qui remporte le dernier plis engrange __10pts__ supplémentaires

## Objectif
L'objectif de ce Kata est de faire un moteur capable de compter les points. 
A vous de déterminer l'architecture la plus adaptée pour y arriver et mettre en place les méthodes pour calculer les points en fonction d'une liste de cartes.

# Auteur
[![build](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cyril-cophignon-b58b5a5b/)
