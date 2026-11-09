# Minuteur de devoir

Une page web toute simple à projeter en classe pendant les évaluations, dans l'esprit de Digiscreen ou Classroomscreen.

👉 **En ligne :** https://clementstorne.github.io/minuteur-devoir/

## Fonctionnalités

- **Deux façons de régler le temps** : une durée (avec des raccourcis 10 min, 20 min, 30 min, 45 min, 55 min, 1 h, 2 h) ou une heure de fin.
- **Affichage visuel et numérique** : un anneau qui se vide, avec le temps restant en grand au centre.
- **Code couleur** : l'anneau passe du vert à l'orange, puis au rouge à l'approche de la fin.
- **Pictogramme calculatrice** bien visible : *autorisée* ou *interdite*. On peut changer en cours de devoir en cliquant dessus.
- **Ajustement du temps** avec les boutons −5, −1, +1 et +5 minutes.
- **Pause / reprise** du minuteur.
- **Mode plein écran** : les boutons et le curseur se masquent après quelques secondes d'inactivité.
- **Rappel de l'heure de fin prévue et de l'heure actuelle.**
- **Titre facultatif** affiché en haut de l'écran (par ex. « Évaluation n°3 – Fonctions affines »).
- **Signal sonore** à la fin (désactivable). Le compteur clignote une fois le temps écoulé.
- **Écran maintenu allumé** pendant le devoir, si le navigateur le permet.
- **Mémorisation des derniers réglages** dans le navigateur.

## Raccourcis clavier

| Touche | Action |
| --- | --- |
| `Espace` | Pause / reprise |
| `F` | Plein écran |
| `↑` ou `+` | Ajouter 1 minute |
| `↓` ou `-` | Retirer 1 minute |
| `C` | Calculatrice autorisée / interdite |
| `Entrée` | Lancer le devoir (depuis l'écran de réglage) |

## Utilisation

1. Ouvrir la page et saisir un titre (facultatif).
2. Choisir le mode **Durée** ou **Heure de fin**.
3. Cocher ou non **Calculatrice autorisée** et **Signal sonore à la fin**.
4. Cliquer sur **Lancer le devoir**, puis passer en plein écran (bouton ou touche `F`).
5. Pour arrêter, cliquer deux fois sur **Terminer** : la double confirmation évite les arrêts accidentels.

## Technique

Un seul fichier `index.html` (HTML, CSS et JavaScript), sans dépendance ni installation : seule la police Atkinson Hyperlegible est chargée depuis Google Fonts. La page fonctionne aussi hors ligne si on télécharge le fichier et qu'on l'ouvre dans un navigateur ; dans ce cas, une police système remplace Atkinson Hyperlegible.

Le site est hébergé avec GitHub Pages depuis la branche `main`.
