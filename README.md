# Modèle LaTeX - Page de titre (ULaval)

Ce dépôt contient un exemple de **page de titre en LaTeX** adaptée à des travaux universitaires.

## Contenu

Le document LaTeX génère une page de garde avec :

- Un en-tête et un pied de page colorés.
- Un logo ou une image (par défaut `ulaval.jpg`).
- Les informations du cours :
- Code du cours (`ART-2400`)
- Nom du cours (`Underwater Basket Weaving`)
- Le titre du devoir (`Durability of Spruce Baskets`).
- La date (automatiquement la date de compilation avec `\today`).
- Les informations étudiantes :
- Nom (`John Doe`)
- Numéro d’identification ULaval (`NI. 314 159 265`).

## Dépendances

Pour compiler ce document, vous aurez besoin de :

- **LaTeX** (distribution complète comme TeX Live ou MikTeX)
- Les packages :
- `graphicx` (gestion des images)
- `babel` avec option `french` (traduction automatique des éléments)
- `xcolor` avec option `dvipsnames` pour avoir accès à la couleur ```Goldenrod```

## Instructions de compilation

1. Placez une image (par ex. `ulaval.jpg`) dans le dossier `images/`.
2. Compilez avec `pdflatex` ou `xelatex` :

```bash
pdflatex main.tex
```

Fonctionne également avec ```Texmaker``` et ```Overleaf```.
