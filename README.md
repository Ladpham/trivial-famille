# Trivial du week-end

Quiz familial en équipes, une seule page HTML, sans dépendance.

**Jouer : https://ladpham.github.io/trivial-famille/**

## Règles
- 2 équipes. On commence par 2 questions test qui ne comptent pas, puis 14 questions (3 histoire de France, 2 géographie française, 1 géographie du monde, 2 côté jardin, 2 cinéma, 2 sport, 2 random).
- Question à réponse : une équipe s'engage, on dévoile, 2 points si juste. Personne ne sait : QCM à 4 propositions, 1 point.
- Question chiffrée (date, taille, nombre) : chaque équipe règle son curseur à l'abri des regards et verrouille. La plus proche prend 2 points, même écart = 1 point chacune.
- Le maître du jeu attribue chaque question. Bouton « Corriger » pour annuler.
- Égalité : question subsidiaire chiffrée (gymnastique).
- Raccourcis clavier : Entrée = bouton principal, A / B / N = attribution.

Les scores sont sauvegardés dans le navigateur (localStorage) : on peut fermer l'onglet et reprendre.

## Modifier les questions
Tout est dans `index.html`, tableau `QUESTIONS` (et `TIEBREAK` pour la subsidiaire). Question à réponse : `a` (texte), `choices` (4), `good` (index de la bonne). Question chiffrée : `num` (min, max, pas, unité) et `a` (nombre). Toujours `note` pour l'anecdote. Échauffement dans `WARMUP`.
