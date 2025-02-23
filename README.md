# JavaScript Exercises

## Introduction
Ce projet contient plusieurs exercices en JavaScript visant à renforcer la compréhension de concepts fondamentaux comme les conversions, les boucles, les conditions, et les algorithmes mathématiques.

## Exercices

### 1. Conversion de températures
**Objectif :** Écrire une fonction `degreC` qui convertit une température en degrés Fahrenheit en degrés Celsius.
- **Formule utilisée :** `tempC = (5/9) * (tempF - 32)`
- **Exemple d'exécution :**
  ```sh
  Une température en Fahrenheit : 60.0
  Cette température équivaut à 15.6 degrés Celsius
  ```

### 2. Conversion de durées
**Objectif :** Écrire une fonction `hjms` qui convertit un nombre de secondes donné en jours, heures, minutes et secondes.
- **Exemple d'exécution :**
  ```sh
  Une durée en secondes : 235789
  Cette durée équivaut à 2 jours 17 heures 29 minutes 49 secondes
  ```

### 2-bis. Amélioration de la conversion de durées
**Objectif :** Modifier la fonction `hjms` pour omettre les valeurs nulles et afficher les unités au singulier si nécessaire.
- **Exemple d'exécution :**
  ```sh
  Une durée en secondes : 3621
  Cette durée équivaut à 1 heure 21 secondes
  ```

### 3. Classer 3 nombres
**Objectif :** Écrire une fonction `troisNombres` qui classe trois nombres donnés dans l'ordre croissant.
- **Exemple d'exécution :**
  ```sh
  1er nombre : 14
  2ème nombre : 10
  3ème nombre : 17
  Les nombres dans l'ordre croissant : 10 14 17
  ```

### 4. Affichage de motifs - escaliers
**Objectif :** Afficher un motif triangulaire en utilisant :
- Une fonction `triangle1` avec des boucles `while`
- Une fonction `triangle2` avec des boucles `for`
- **Exemple de sortie :**
  ```sh
  *
  **
  ***
  ****
  *****
  ******
  ```

### 4-bis. Affichage de motifs - pyramides
**Objectif :** Modifier le programme précédent pour afficher une pyramide au lieu d'un triangle.
- **Exemple de sortie :**
  ```sh
        *
       ***
      *****
     *******
    *********
   ***********
  *************
  ```

### 5. Tester si un nombre est premier
**Objectif :** Écrire une fonction `Premier` qui teste si un nombre est premier ou non.
- **Exemple d'exécution :**
  ```sh
  Un entier positif : 7
  7 est un nombre premier
  ```

### 6. Suite de Fibonacci
**Objectif :**
- `Fibo1` : Calculer le n-ième terme de la suite de Fibonacci.
- `Fibo2` : Trouver le premier terme de la suite supérieur à une valeur donnée.

### 7. Valeur approchée de la racine carrée
**Objectif :** Écrire une fonction `Raca1` qui estime la racine carrée d'un nombre entre 1 et 100 à l'aide de la méthode de Newton.
- **Exemple d'exécution :**
  ```sh
  Pour un nombre A entre 1 et 100: 19.23
  Valeur approchée de la racine carrée = 4.385202389856321
  ```

## Technologies utilisées
- **Langage :** JavaScript 
- **Outils recommandés :** Node.js, navigateur web avec console JavaScript

## Comment exécuter le projet
1. Clonez ce dépôt :
   ```sh
   git clone https://github.com/TP3TW-XML.git
   ```
2. Exécutez le fichier correspondant à l'exercice avec Node.js ou dans la console du navigateur.
3. Suivez les instructions affichées pour entrer les valeurs nécessaires.


