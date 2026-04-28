# Catalogue de cartes PWA

Application PWA prête pour GitHub Pages.

## Données

Les cartes ne sont pas intégrées dans le code. Elles doivent être importées depuis un fichier JSON sur l'appareil Android.

Fichier attendu : une liste JSON de cartes, par exemple :

```json
[
  {
    "name": "Bouclier magique",
    "mana_cost": "1",
    "type": "Enchantement : Artefact et",
    "rarity": "uncommon",
    "rules_text": "...",
    "flavor_text": "",
    "power": "",
    "toughness": "",
    "loyalty": "",
    "illustrator": "Coveney",
    "card_number": "26",
    "notes": "",
    "id": "card-0001"
  }
]
```

## Fonctions

- Liste en tableau par défaut
- Tri par colonne
- Bouton Edit à gauche du titre
- Fiche détaillée avec édition locale
- Choix des colonnes visibles
- Recherche globale
- Filtres par rareté et type
- Suppression locale
- Export JSON de la vue ou de toute la base locale
- Stockage local dans le navigateur Android

## GitHub Pages

1. Déposer ces fichiers à la racine du dépôt.
2. Aller dans Settings > Pages.
3. Choisir Deploy from a branch.
4. Sélectionner main et /root.
5. Ouvrir l’URL publiée dans Chrome Android.
6. Installer l’application depuis le menu Chrome.

## Confidentialité

Ne pas publier le fichier JSON de données sur GitHub si les cartes doivent rester privées.
