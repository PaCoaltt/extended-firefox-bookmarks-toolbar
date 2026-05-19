# extended-firefox-bookmarks-toolbar

## English

Displays Firefox personal toolbar bookmarks on **2 or more lines**.

### Content

- `chrome/userChrome.css`: style file to copy into your Firefox profile.

### Installation

1. Open `about:config` in Firefox.
2. Set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.
3. Open your profile folder (`about:profiles` → "Root Directory" → "Open Folder").
4. Create a `chrome` folder if it does not exist.
5. Copy `chrome/userChrome.css` from this repository into that folder.
6. Restart Firefox.

### Configure the number of lines

In `userChrome.css`, edit:

```css
--bookmarks-toolbar-lines: 2;
```

Examples:

- `2` for 2 lines
- `3` for 3 lines
- `4` for 4 lines

If needed, also adjust the item height:

```css
--bookmarks-toolbar-item-height: 30px;
```

---

## Français

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
