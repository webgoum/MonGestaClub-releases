# MonGestaClub — Site public & téléchargements

Ce dépôt **public** héberge deux choses, et **aucun code source applicatif** :

1. **Le site de présentation** (vitrine + démo jouable), publié via **GitHub Pages**
   sur https://www.mongestaclub.fr
2. **Les installateurs** (macOS & Windows), publiés comme **assets de GitHub Releases**.

Le code source de l'application est conservé dans un dépôt **privé** séparé.

## Contenu

- `index.html` — page de présentation
- `installation.html` — guide de première ouverture (Mac & Windows)
- `demo/` — démo jouable (application web en mode démonstration, données locales au navigateur)
- `shots/` — captures d'écran
- `CNAME` — domaine personnalisé (`www.mongestaclub.fr`)
- `.nojekyll` — désactive le traitement Jekyll de GitHub Pages

## Téléchargements (release `v1.0.5`)

Installeurs non signés (voir le guide *Première ouverture*) :

- [`MonGestaClub-1.0.5-mac-arm64.dmg`](https://github.com/webgoum/MonGestaClub-releases/releases/download/v1.0.5/MonGestaClub-1.0.5-mac-arm64.dmg) — macOS Apple Silicon (M1–M4)
- [`MonGestaClub-1.0.5-mac-intel.dmg`](https://github.com/webgoum/MonGestaClub-releases/releases/download/v1.0.5/MonGestaClub-1.0.5-mac-intel.dmg) — macOS Intel
- [`MonGestaClub-1.0.5-windows.exe`](https://github.com/webgoum/MonGestaClub-releases/releases/download/v1.0.5/MonGestaClub-1.0.5-windows.exe) — Windows 10 / 11
- [`MonGestaClub-1.0.5-linux.AppImage`](https://github.com/webgoum/MonGestaClub-releases/releases/download/v1.0.5/MonGestaClub-1.0.5-linux.AppImage) — Linux (AppImage 64 bits, rendre exécutable si nécessaire)

## Mise à jour

Le contenu est synchronisé depuis le dossier `presentation/` du dépôt privé.
À chaque version : copier `presentation/` ici, committer/pousser, puis publier la release
correspondante avec les nouveaux installateurs.

© 2026 Thierry.C — Tous droits réservés.
