# Montoni — Initiative IA — Cartographie des processus

Maquette interactive en un seul fichier HTML (Three.js), construite à partir des 30 entrevues de départements.

Ouvrir `Cartographie des processus.html` dans un navigateur (aucun serveur requis, Three.js chargé depuis cdnjs).

## Contenu

- Scène 3D : cube central et 16 départements en hologrammes cliquables.
- Par département : objectifs et indicateurs (cible / réel avec source d'entrevue), ressources humaines, processus, diagnostics.
- Par processus : chaîne EPC (qui, entrants, étape, sortants, systèmes) et fenêtre de droite avec indicateurs de performance, goulots d'étranglement (cause, cinq pourquoi, Ishikawa) et temps de cycle par étape (14 dimensions, éditables).
- Tableau de bord : rapport des objectifs globaux avec cible, écart (rouge pastel si défavorable) et réel par indicateur, sources et processus liés.

Les saisies faites dans l'interface (mesures, pistes d'amélioration, participants) sont conservées dans le localStorage du navigateur.
