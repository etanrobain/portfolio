# Portfolio BUT R&T — Etan Robain

Portfolio personnel présentant mes compétences en **Réseaux & Télécommunications** (BUT R&T) à travers les **apprentissages critiques (AC)** du référentiel. Site statique, bilingue 🇫🇷 / 🇬🇧, hébergé sur GitHub Pages.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-deployed-222?logo=github)

> 🔗 **Site en ligne :** `https://<ton-pseudo>.github.io/<nom-du-dépôt>/`
> _(à remplacer par l'URL réelle de ton dépôt)_

---

## À propos

Le site regroupe en un seul endroit les **5 grandes compétences** du BUT R&T. Chaque compétence a sa page dédiée, où les apprentissages critiques sont présentés sous forme de menus déroulants. Chaque AC s'ouvre sur un **retour réflexif en 6 points** (ce que j'ai fait, pourquoi, comment, mes difficultés, ce que j'en ai appris, ce que je ferais autrement).

## Fonctionnalités

- **Bilingue** — version française (`index-fr.html`) et anglaise (`index.html`) avec sélecteur de langue.
- **5 pages de compétences** — Administrer, Connecter, Coder, Sécuriser, Superviser.
- **Apprentissages critiques détaillés** — chaque AC en accordéon natif (`<details>`), avec une grille de retour réflexif.
- **Thème sombre « premium »** — design noir & blanc, effets de verre et reflets, entièrement en CSS.
- **Responsive** et respect de `prefers-reduced-motion` (animations coupées pour qui les désactive).
- **Sans framework ni build** — HTML/CSS, juste un peu de JavaScript pour le changement de langue.

## Structure du projet

```text
.
├── assets/
│   ├── img/
│   │   └── favicon.ico          # Favicon du site
│   └── style.css                # Feuille de style unique (thème + grille réflexive)
├── index.html                   # Accueil (anglais)
├── index-fr.html                # Accueil (français)
├── mentions-legales.html        # Mentions légales
├── skill-administer.html        # Compétence : Administrer
├── skill-connect.html           # Compétence : Connecter
├── skill-code.html              # Compétence : Coder
├── skill-secure.html            # Compétence : Sécuriser
├── skill-monitor.html           # Compétence : Superviser
└── README.md
```

## Les compétences

| Page | Compétence | Apprentissages critiques |
|------|------------|--------------------------|
| `skill-administer.html` | Administrer | 6 AC |
| `skill-connect.html` | Connecter | 5 AC |
| `skill-code.html` | Coder | 5 AC |
| `skill-secure.html` | Sécuriser | 6 AC |
| `skill-monitor.html` | Superviser | 2 AC |

> **24 apprentissages critiques** au total, chacun accompagné de son retour réflexif.

## Technologies

- **HTML5** — pages statiques, accordéons natifs `<details>` / `<summary>`.
- **CSS3** — variables (`:root`), Grid & Flexbox, `backdrop-filter`, animations.
- **JavaScript (vanilla)** — uniquement pour le sélecteur de langue.

## Lancer le projet en local

Aucune dépendance à installer. Le plus simple :

```bash
# Cloner le dépôt
git clone https://github.com/<ton-pseudo>/<nom-du-dépôt>.git
cd <nom-du-dépôt>
```

Puis ouvre `index.html` dans ton navigateur.

Pour un rendu identique à la production (chemins relatifs, etc.), tu peux lancer un petit serveur local :

```bash
# Python 3
python -m http.server 8000
# puis ouvrir http://localhost:8000
```

## Déploiement

Le site est publié via **GitHub Pages** :

1. Dépôt → **Settings** → **Pages**.
2. Source : la branche `main`, dossier `/ (root)`.
3. Chaque `commit` sur `main` met le site à jour automatiquement.

## Auteur

**Etan Robain** — étudiant en BUT Réseaux & Télécommunications
📧 etanrobain.pro@gmail.com

## Licence

© 2025 Etan Robain. Tous droits réservés.
Le code et les contenus de ce portfolio ne peuvent être réutilisés sans autorisation.
