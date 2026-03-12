# CV - KAKPO Oswald

> Curriculum Vitae personnel développé en HTML / CSS pur — sans JavaScript.  
> Réalisé dans le cadre du cours de développement web — Licence 1 SIL, ESCAE-Bénin, Promotion 2026.

---

## Aperçu

Ce projet est une petite application web statique composée de deux vues :

- **CV** — présentation complète du profil : informations personnelles, compétences, langues, formation et centres d'intérêt.
- **Liste des étudiants** — tableau des 46 étudiants de la classe Licence 1 SIL / SI / IA, Promotion 2026.

La navigation entre les deux vues est gérée entièrement en CSS pur grâce à la technique du **radio button hack** (`input:checked ~ sélecteur`), sans une seule ligne de JavaScript.

---

## Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| HTML5 | Structure sémantique de la page |
| CSS | Mise en page, navigation, responsive |

---

## Structure du projet

```
cv-kakpo-oswald/
│
└── index.html       # Fichier unique — contient HTML + CSS
```

---

## Fonctionnalités

- Navigation par onglets (CV / Liste) en **CSS pur** — aucun JavaScript
- Photo de profil dans l'en-tête
- Compétences organisées par catégorie : développement web et outils bureautiques
- Ligne de KAKPO Oswald mise en évidence dans le tableau
- Design responsive (adapté mobile / tablette / desktop)
- Code propre, commenté et structuré

---

## Lancer le projet

Aucune installation requise. Il suffit d'ouvrir le fichier dans un navigateur :

```bash
# Cloner le dépôt
git clone https://github.com/OswaldKakpo/cv-kakpo-oswald.git

# Ouvrir le fichier
cd cv-kakpo-oswald
open index.html
```

Ou simplement double-cliquer sur `index.html`.

---

## Auteur

**KAKPO Oswald**  
Étudiant en Licence 1 SIL — ESCAE-Bénin  
gottioswald@gmail.com

---

## Licence

Projet personnel — usage éducatif.
