# Exercice 1 — Prénom + Nom + Séparateur

## Objectif
Demander à l’utilisateur son prénom, son nom et un séparateur personnalisé, puis afficher les deux valeurs avec ce séparateur.

## Code
```python
prenom = input("Entrez votre prénom : ")
nom = input("Entrez votre nom : ")
sep = input("Entrez un séparateur personnalisé : ")

print(prenom, nom, sep=sep)
