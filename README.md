# 🐍 Python-Algo-Sprint - logic & Algorithm Fundamentals

**Dépôt académique intensif** regroupant 60 algorithmes résolus en 48 heures lors de ma rentrée en Bachelor Full Stack.
Ce projet démontre une capacité d'apprentissage rapide et une maîtrise des structures fondamentales de la programmation impérative.

## 🎯 Contexte & Challenge

Ce "Sprint" a été mon premier contact intensif avec Python. L'objectif était de résoudre un maximum de problèmes logiques (parmi un total de 100) en un temps record pour automatiser les réflexes de développement.

**Indicateurs clés :**

- **Volume :** 60 scripts fonctionnels intégrés dans un moteur d'exécution centralisé.
- **Vitesse :** 30 exercices validés par jour.
- **Diversité :** Arithmétique, logique booléenne, manipulation de chaînes, suites mathématiques et structures de données.

## 🛠️ Stack Technique

- **Langage :** Python 3.10+
- **Architecture :** Programmation procédurale et fonctionnelle.
- **Outils :** Bibliothèque `random` pour les simulations.

## 🚀 Panorama des Concepts Validés

L'évolution dans le fichier `Main.py` suit une courbe de difficulté croissante :

### 1. Fondamentaux & Entrées/Sorties (Exo 1 à 21)

- Interaction utilisateur via `input()` et formatage de chaînes.
- Opérations arithmétiques de base et conversions d'unités (Euro/Dollar, HT/TTC).

### 2. Logique Conditionnelle & Flux (Exo 22 à 30)

- Implémentation de règles métier (Validation de notes, catégories d'âge).
- Utilisation des structures `if / elif / else`.

### 3. Algorithmes Itératifs (Exo 31 à 41)

- Maîtrise des boucles `for` et `while`.
- Génération de formes géométriques (Carrés, Pyramides d'étoiles).
- Algorithmes de recherche de carrés parfaits.

### 4. Structures de Données & Mathématiques (Exo 42 à 60)

- **Listes :** Calculs de moyennes (Exo 42), recherche de Min/Max (Exo 43).
- **String Parsing :** Inversion de mots (Exo 45), comptage de voyelles (Exo 44).
- **Maths avancées :** Nombres premiers (Exo 50), Suite de Fibonacci (Exo 51), Triangle de Pascal (Exo 52), et PGCD (Exo 60).

## 🏗️ Focus Technique : Le Carré Magique (Exo 53)

L'un des exercices les plus complexes du sprint a été la validation d'un **Carré Magique**.

- **Challenge :** Vérifier que la somme de chaque ligne, chaque colonne et des deux diagonales est identique.
- **Logique :** Utilisation de boucles imbriquées pour parcourir une matrice 3x3 et comparaison systématique à une `somme_cible`.

## 🧠 Challenges Techniques Résolus

### Modularité et Architecture "Main"

Pour gérer 60 exercices dans un seul fichier sans que cela devienne illisible, j'ai implémenté un **point d'entrée centralisé**.

- _Solution :_ Utilisation de la structure `if __name__ == "__main__":` associée à une fonction `main()` qui fait office de routeur. L'utilisateur saisit le numéro de l'exercice, et le script appelle la fonction correspondante.

### Algorithmique de recherche (PGCD)

L'exercice 60 demandait de trouver le plus grand diviseur commun entre deux nombres.

- _Solution :_ J'ai opté pour une approche par comparaison de listes de diviseurs, démontrant une compréhension des intersections d'ensembles de données.

## ⚙️ Utilisation

1. **Cloner le projet :**

```bash
git clone [https://github.com/EnzoRouet/CODA-Exercice-Python-Enzo]
```

2. **Lancer le moteur :**

```Bash
python Main.py
```

3. **Choisir un exercice : Saisissez un nombre entre 1 et 61 pour exécuter l'algorithme souhaité.**
