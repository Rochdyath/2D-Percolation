# 2D-Percolation
Y a t - il percolation ?

Etant donnée une grille dont chaque case peut être soit un obstacle, soit une case vide, existe-t-il un chemin (évitant les obstacles) de la première à la dernière ligne de la grille? Si oui, on dit qu’il y a percolation.

Supposons que chaque case ait une probabilité p d’être un obstacle. Alors:

    • Si p = 0, toutes les cases sont vides, il y a toujours percolation.
  
    • Si p = 1, toutes les cases sont des obstacles, il n’y a jamais percolation.
  
  On cherche à savoir ce qui se passe pour des valeurs intermédiaires de p.

Pour cela nous allons travailler avec des grilles générées aléatoirement pour différentes valeurs de p. Pour chaque valeur de p qui nous intéresse, nous cherchons à estimer la probabilité qu’il y ait percolation sur une grille de taille N × N. Nous effectuerons donc de nombreuses simulations et calculerons la proportion de grilles ayant cette propriété (méthode de Monte-Carlo).
