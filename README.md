# Random_Guess


# 🎯 Devinez le Nombre

Un mini-jeu en Python où l'utilisateur doit deviner un nombre choisi aléatoirement entre 1 et 100.  
Le jeu lui indique si la tentative est trop basse ou trop élevée, jusqu'à deviner correctement.

---

## 🔍 Objectif du Projet

- Renforcer les bases de la programmation Python
- S'exercer avec les boucles `while`, les conditions `if/else` et les fonctions `input()` / `random.randint()`
- Créer une interaction console ludique et informative

---

## 🧪 Méthodologie

### 1️⃣ Génération du Nombre Aléatoire
- Utilisation du module `random`
- Nombre généré : `random.randint(1, 100)`

### 2️⃣ Récupération des Tentatives de l’Utilisateur
- Lecture via `input()`
- Conversion en entier avec `int()`

### 3️⃣ Boucle de Jeu
- Répéter jusqu'à ce que la saisie corresponde au nombre
- Donner un indice après chaque tentative :
  - ✅ Trop élevé
  - ✅ Trop bas
  - ✅ Bravo, vous avez deviné le bon nombre !

### 4️⃣ Fin du Jeu
- Affichage personnalisé lorsque l’utilisateur réussit
- Optionnel : nombre d’essais réalisés







