
Here's the README.md content you can copy directly:

markdown
# #MTSKTICH — Votre voix. Vos droits. Notre engagement.

> **"MTSKTICH"** (مْتْسْكْتِيش) signifie **"Ne reste pas silencieuse"** en darija marocaine.

---

## Table des matières

- [À propos du projet](#à-propos-du-projet)
- [Le problème](#le-problème)
- [La solution proposée](#la-solution-proposée)
- [Fonctionnalités principales](#fonctionnalités-principales)
- [Technologies utilisées](#technologies-utilisées)
- [Structure du projet](#structure-du-projet)
- [Installation et lancement](#installation-et-lancement)
- [Auteure](#auteure)

---

## À propos du projet

**#MTSKTICH** est un prototype de plateforme web dédiée aux **droits des femmes**, à la **responsabilité** et à la **justice** au Maroc. Le site vise à accompagner les femmes qui ont déposé plainte ou qui souhaitent entamer une démarche juridique, en leur offrant un espace d'information, d'orientation et de suivi transparent.

> **Note** : Ce projet est un **prototype** avec des **données fictives**, réalisé dans un cadre pédagogique / de sensibilisation.

---

## Le problème

Déposer plainte est une démarche difficile et courageuse. Pourtant, une fois la plainte déposée, de nombreuses femmes se retrouvent confrontées à :

- **Le silence institutionnel** : ne pas savoir ce que devient leur dossier.
- **L'attente interminable** : les jours passent sans information claire.
- **Le poids du silence** : qui suit le dossier ? Pourquoi ce délai ? Vers qui se tourner ?
- **L'isolement** : se sentir seule face à une procédure complexe.
- **Le manque de repères** : ne pas comprendre ses droits ni les étapes à venir.

> *« Une plainte ne devrait jamais devenir un dossier oublié. »*

---

## La solution proposée

**#MTSKTICH** propose un accompagnement humain, transparent et sans jugement, articulé autour de plusieurs axes :

### 1. Comprendre ses droits
Des repères accessibles pour mettre des mots sur sa situation et mieux s'orienter dans le système juridique.

### 2. Ne plus avancer seule
Comprendre le rôle des associations et des professionnels qui peuvent accompagner chaque étape.

### 3. Rendre le suivi visible
Savoir **qui fait quoi**, **à quelle date** et **quelle est la prochaine étape** — pour que chaque démarche ait une suite concrète.

### 4. Un accompagnement à votre rythme
- Sans jugement.
- Sans promesse impossible.
- En respectant la liberté de chaque femme (rythme, informations partagées).

### 5. Le mur des voix
Un espace de récits et de solidarité où les femmes peuvent se sentir moins seules.

---

## Fonctionnalités principales

| Section | Description |
|---|---|
| **Accueil** | Présentation du projet, message fort et appel à l'action |
| **Mes droits** | Informations sur les droits des femmes et les démarches possibles |
| **Agir ensemble** | Rôle des associations, professionnels et soutiens |
| **Mon espace** | Espace personnel pour préparer sa demande et suivre son dossier |
| **Le mur des voix** | Témoignages et récits pour briser l'isolement |
| **Besoin d'aide ?** | Bouton d'accès rapide à l'accompagnement |

### Parcours utilisateur illustré sur la page d'accueil :

1. **Le courage de parler** — Une femme dépose plainte et espère être entendue.
2. **Le temps de l'attente** — Les jours passent, les informations deviennent difficiles à obtenir.
3. **Le poids du silence** — Qui suit le dossier ? Pourquoi ce délai ?
4. **Une suite à construire** — Comprendre, être orientée et identifier une prochaine étape concrète.

---

## Technologies utilisées

### Frontend
- **HTML5** — Structure sémantique des pages
- **CSS3** — Styles personnalisés (`index.css`)
- **Tailwind CSS v4** — Framework utilitaire pour le design (`input.css` → `output.css`)
- **Flowbite** — Composants et thème Tailwind
- **Google Fonts (Inter)** — Typographie moderne et lisible

### Outils de build
- **Tailwind CLI** — Compilation du CSS (`input.css` → `output.css`)

### Design
- Palette de couleurs personnalisée via variables CSS :
  - `--color-alpha: #5f2f50` (violet profond)
  - `--color-beta: #f39139` (orange chaleureux)
  - `--color-bg1: #fffaf5` (fond clair)
  - `--color-bg2: #f8f0f4` (fond rosé)
  - `--color-bg3: #72245d` (violet accent)

### Icônes
- **Bootstrap Icons** (SVG inline)

---

## Structure du projet

```text
/
├── index.html # Page d'accueil
├── public/
│ ├── css/
│ │ ├── input.css # Source Tailwind + variables
│ │ ├── output.css # CSS compilé
│ │ └── index.css # Styles personnalisés
│ ├── images/
│ │ ├── image1.png # Illustration section héro
│ │ └── image.png # Illustration mur des voix
│ └── pages/
│ ├── Mes droits.html
│ ├── Agir ensemble.html
│ └── Mon espace.html
└── README.md
```


---

## Installation et lancement

### Prérequis
- Navigateur web moderne
- (Optionnel) **Node.js** et **npm** pour recompiler le CSS Tailwind

### Utilisation simple
Ouvrir `index.html` directement dans un navigateur.

### Pour modifier les styles (Tailwind)
```bash

# Installer les dépendances (si package.json présent)

npm install

# Compiler le CSS en mode watch
npx @tailwindcss/cli -i ./public/css/input.css -o ./public/css/output.css --watch
```

Mentions et limites
Ce site est un prototype de sensibilisation. Il ne remplace pas un accompagnement juridique professionnel. Les informations présentées sont fictives et destinées à illustrer le concept.

Notre conviction
« Le silence ne doit pas être la suite de votre histoire. »

Pour que chaque voix soit entendue,
et que chaque démarche ait une suite.

>© 2026 #MTSKTICH · Projet SARAH ACHAHOUI
