# extended-firefox-bookmarks-toolbar

Permet d'afficher les favoris de la barre personnelle Firefox sur **2 lignes ou plus**.

## Contenu

- `chrome/userChrome.css`: style à copier dans le profil Firefox.

## Installation

1. Ouvrir `about:config` dans Firefox.
2. Activer `toolkit.legacyUserProfileCustomizations.stylesheets` à `true`.
3. Ouvrir le dossier de profil (`about:profiles` → "Dossier racine" → "Ouvrir le dossier").
4. Créer un dossier `chrome` s'il n'existe pas.
5. Copier `chrome/userChrome.css` de ce dépôt dans ce dossier.
6. Redémarrer Firefox.

## Configuration du nombre de lignes

Dans `userChrome.css`, modifier :

```css
--bookmarks-toolbar-lines: 2;
```

Exemples :

- `2` pour 2 lignes
- `3` pour 3 lignes
- `4` pour 4 lignes

Si nécessaire, ajuster aussi la hauteur d'un élément :

```css
--bookmarks-toolbar-item-height: 30px;
```
