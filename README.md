# Checkpoint – Analyse d’une Phrase

## Objectif
Ce checkpoint consiste à écrire un algorithme qui lit une phrase caractère par caractère, se terminant par un point (`.`), afin de déterminer :
- La longueur de la phrase (nombre de caractères)
- Le nombre de mots (séparés par un seul espace)
- Le nombre de voyelles

##  Contraintes
- Chaque caractère est traité séparément
- Le dernier caractère est obligatoirement un point (`.`)
- Utilisation de **trois variables comme compteurs**
- Lecture caractère par caractère

##  Principe de la solution
L’algorithme lit les caractères un à un jusqu’à rencontrer le point.
Trois compteurs sont utilisés :
- Un compteur pour les caractères
- Un compteur pour les mots
- Un compteur pour les voyelles

##  Contenu du dépôt
- `phrase.algo` : Algorithme qui réalise l’analyse de la phrase
- `README.md` : Description du checkpoint

##  Résultat attendu
À la fin de l’exécution, l’algorithme affiche :
- Le nombre total de caractères
- Le nombre total de mots
- Le nombre total de voyelles
