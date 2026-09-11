# Trivial du week-end

Quiz familial en équipes, une seule page HTML, sans dépendance.

**Jouer : https://ladpham.github.io/trivial-famille/**

## Règles
- 2 équipes, 14 questions (3 histoire de France, 2 géographie française, 1 géographie du monde, 2 côté jardin, 2 cinéma, 2 sport, 2 random).
- Réponse ouverte : une équipe s'engage, on dévoile, 2 points si juste.
- Personne ne sait : QCM à 4 propositions, 1 point.
- Le maître du jeu attribue chaque question à A, B ou personne. Bouton « Corriger » pour annuler.
- Égalité : question subsidiaire (gymnastique).
- Raccourcis clavier : Entrée = bouton principal, A / B / N = attribution, flèche gauche = corriger.

Les scores sont sauvegardés dans le navigateur (localStorage) : on peut fermer l'onglet et reprendre.

## Modifier les questions
Tout est dans `index.html`, tableau `QUESTIONS` (et `TIEBREAK` pour la subsidiaire). Chaque entrée : catégorie, emoji, question, réponse ouverte, 4 choix, index de la bonne réponse, anecdote.
