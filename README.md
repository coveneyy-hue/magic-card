# Liste de cartes PWA

Application PWA statique pour consulter une liste de cartes.

## Fonctions

- Recherche plein texte
- Filtres par rareté et type
- Suppression locale par carte
- Restauration des suppressions
- Export JSON des cartes affichées
- Installation sur Android via Chrome
- Mode hors ligne après la première visite

## Hébergement sur GitHub Pages

1. Créer un dépôt GitHub.
2. Envoyer ces fichiers à la racine du dépôt.
3. Aller dans Settings > Pages.
4. Choisir Deploy from a branch.
5. Sélectionner la branche `main` et le dossier `/root`.
6. Ouvrir l’URL GitHub Pages générée.

## Installation Android

1. Ouvrir l’URL GitHub Pages dans Chrome sur Android.
2. Menu Chrome > Ajouter à l’écran d’accueil ou Installer l’application.
3. L’application sera disponible comme une app Android.

## Note de confidentialité

Un dépôt public rendra le contenu du fichier visible publiquement. Utiliser un dépôt privé avec GitHub Pages privé seulement si le compte GitHub le permet, ou retirer les informations sensibles avant publication.


## Données locales sur Android

Cette version ne publie pas les cartes dans le code de l’application.

1. Hébergez les fichiers de l’application sur GitHub Pages.
2. Copiez `cartes-donnees-import.json` sur votre téléphone Android.
3. Ouvrez l’application installée.
4. Touchez **Importer JSON**.
5. Sélectionnez `cartes-donnees-import.json`.

Les cartes sont ensuite stockées dans le navigateur de l’app sur l’appareil, via `localStorage`. Le dépôt GitHub peut donc rester sans données de cartes, tant que vous n’ajoutez pas le JSON au dépôt.
