# Maze Generator

Générateur de labyrinthes **animé**, en JavaScript pur et Canvas, sans aucune dépendance.

Le labyrinthe se construit sous vos yeux avec l'algorithme du **backtracking récursif** (parcours en profondeur avec pile) : on avance vers une cellule voisine non visitée en cassant le mur, et on revient en arrière quand on est bloqué. Le résultat est un labyrinthe *parfait* : un seul chemin entre deux cases.

## Lancer

Ouvrir `index.html` dans un navigateur, c'est tout.

## Fichiers

- `index.js` : classes `Maze` et `Cell`, génération et dessin pas à pas
- `index.css` : mise en page du canvas
