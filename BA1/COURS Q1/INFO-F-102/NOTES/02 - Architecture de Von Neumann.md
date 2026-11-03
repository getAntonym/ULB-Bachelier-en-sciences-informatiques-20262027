# Un premier programme — Architecture de Von Neumann
## Un  programme Python 


```python
"""
Calcul des racines d'une équation du second degré
"""
__author__ = "Thierry Massar"
__date__ = "22 aout 2012"

from math import sqrt

a = float(input("valeur de a : "))
b = float(input("valeur de b : "))  # Entrée de données
c = float(input("valeur de c : "))

delta = b**2 - 4*a*c

if delta < 0:
    print("Pas de racines reelles")
elif delta == 0:
    print("Une solution reelle : x = ", -b/(2*a))
else:
    x1 = (-b - sqrt(delta))/(2*a)
    x2 = (-b + sqrt(delta))/(2*a)
```
### Besoins

1. Entrée de données : `a`, `b`, `c`.
2. Stocker les données et les résultats des calculs.
3. Afficher les résultats : sortie de données.
4. Effectuer des opérations de base.
5. Stocker le programme.

## Un premier modèle d’ordinateur

Un modèle est une représentation simplifiée d’un système complexe, qu’on utilise pour mieux le comprendre.

### Schéma de l’architecture de Von Neumann
![vonneumann](../REFERENCES/vonneumann.png)

*Figure 1 — L’architecture de Von Neumann.*

## Définitions

> [!NOTE]
> **Processeur — CPU**
>
> Central Processing Unit
>
> Composant qui exécute les programmes.
>
> Il comprend notamment :
>
> - Unité de calcul — ALU  
>   Circuit du CPU qui effectue les opérations arithmétiques et logiques nécessaires pour les instructions.
>
> - Registres  
>   Petites mémoires dans le CPU.
>
> - Unité de contrôle — CU  
>   Coordonne les registres, l’ALU et l’exécution.

> [!NOTE]
> **Mémoire vive ou primaire — RAM**
>
> Stockage pour :
> - les données ;
> - le programme.

## Suite
[03 - Représentation de l’information](03%20-%20Repr%C3%A9sentation%20de%20l%E2%80%99information.md)