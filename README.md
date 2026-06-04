# Rapport de Stage de Fin d'Études - EL MOUKTADIR Mohamed

## 📋 Informations du Rapport

- **Titre** : Conception et développement d'un système de synchronisation incrémentale (PowerTeam)
- **Auteur** : EL MOUKTADIR Mohamed
- **Diplôme** : Ingénieur d'État - Spécialité Génie Informatique
- **École** : École Nationale des Sciences Appliquées de Marrakech (ENSA-M)
- **Entreprise** : Tamtam International, Marrakech
- **Année Universitaire** : 2025/2026
- **Date de Soutenance** : 07/06/2026

---

## 📁 Structure du Projet

```
Rapport_PFE_2026-/
├── main.tex                 # Fichier principal LaTeX
├── preamble.tex            # Configuration et packages LaTeX
├── references.bib          # Bibliographie
├── glossary.tex            # Glossaire des acronymes
├── pages/                  # Pages préliminaires
│   ├── page-garde.tex
│   ├── dedicasse.tex
│   ├── remerciements.tex
│   ├── abstract.tex
│   ├── resume.tex
│   ├── resume-arabe.tex
│   ├── introduction-generale.tex
│   ├── conclusion.tex
│   ├── liste-figures-tableaux.tex
│   └── liste-abreviations.tex
├── chapters/               # Chapitres principaux
│   ├── 01-etude-prealable/
│   │   ├── page-titre.tex
│   │   └── contenu.tex
│   ├── 02-analyse-conception/
│   │   ├── page-titre.tex
│   │   └── contenu.tex
│   ├── 03-environnement-technologies/
│   │   ├── page-titre.tex
│   │   └── contenu.tex
│   ├── 04-realisation/
│   │   ├── page-titre.tex
│   │   └── contenu.tex
│   └── 05-bilan/
│       ├── page-titre.tex
│       └── contenu.tex
├── images/                 # Images et figures
├── annexes/                # Annexes
├── compile.sh             # Script de compilation
└── README.md              # Ce fichier
```

---

## 🛠 Installation et Compilation

### Prérequis

- **TeX Live** ou **MiKTeX** installé
- **XeLaTeX** pour la compilation
- **Graphviz** (optionnel, pour les diagrammes)

### Sur Ubuntu/Linux

```bash
sudo apt-get install texlive-full
```

### Compilation

```bash
# Compilation simple
xelatex main.tex

# Avec bibliographie
xelatex main.tex
bibtex main
xelatex main.tex
xelatex main.tex

# Script de compilation automatique
bash compile.sh
```

---

## 📝 Contenu des Chapitres

### Chapitre 1 : Étude Préalable
- Contexte général du projet
- Présentation de l'entreprise Tamtam International
- Formation dispensée
- Présentation du sujet de stage
- Méthodologie adoptée (SCRUM)
- Gestion des tâches et suivi

### Chapitre 2 : Analyse et Conception
- Présentation de l'UML
- Diagrammes de cas d'utilisation
- Diagrammes de classe
- Diagrammes de séquence

### Chapitre 3 : Environnement, Technologies et Outils de Développement
- Analyse des besoins (fonctionnels et non-fonctionnels)
- Architecture physique du système
- Architecture logique et hexagonale
- Architecture de synchronisation Delta
- Structure du projet
- Frameworks et technologies utilisées

### Chapitre 4 : Réalisation et Implémentation
- Présentation des interfaces graphiques
- Démonstration des fonctionnalités
- Captures d'écran avec explications

### Chapitre 5 : Bilan Professionnel, Technique et Personnel
- Bilan professionnel et technique
- Bilan personnel
- Apprentissages et compétences acquises

---

## 📚 Pages Préliminaires

1. **Page de Garde** : Informations officielles du rapport
2. **Dédicace** : Dédicace personnelle
3. **Remerciements** : Remerciements aux superviseurs et entreprise
4. **Résumé** (Français, Anglais, Arabe) : Synthèse du travail
5. **Table des Matières** : Générée automatiquement
6. **Liste des Figures et Tableaux** : Générée automatiquement
7. **Introduction Générale** : Contexte et objectifs généraux

---

## 🔗 Technologie et Stack

### Backend
- **Langage** : PHP
- **Framework** : Symfony
- **ORM** : Doctrine
- **Base de Données** : MySQL

### Frontend
- **Framework** : React.js
- **State Management** : Redux
- **HTTP Client** : Axios
- **Styling** : Sass

### DevOps
- **Contrôle de Version** : Git & GitHub
- **CI/CD** : GitHub Actions
- **Serveur Web** : Nginx
- **Système d'Exploitation** : Ubuntu 24.04

### Architecture
- **Pattern** : Architecture Hexagonale + CQRS
- **Méthodologie** : SCRUM

---

## 📖 Glossaire et Acronymes

Tous les acronymes et termes techniques sont définis dans le fichier `glossary.tex` et la section "Liste des Abréviations".

---

## 📊 Diagrammes et Figures

Le rapport contient :
- ✅ Diagrammes de cas d'utilisation UML
- ✅ Diagrammes de classe UML
- ✅ Diagrammes de séquence UML
- ✅ Diagramme de Gantt du projet
- ✅ Captures d'écran des interfaces
- ✅ Architectures (physique, logique, Delta Sync)

Toutes les images sont placées dans le dossier `images/` et référencées dans les chapitres.

---

## ✅ Checklist de Compilation

- [ ] Installer TeX Live ou MiKTeX
- [ ] Cloner le dépôt
- [ ] Placer les images dans le dossier `images/`
- [ ] Compiler avec `xelatex main.tex`
- [ ] Générer la bibliographie avec `bibtex main`
- [ ] Compiler à nouveau (2-3 fois)
- [ ] Vérifier le PDF généré

---

## 📧 Contact et Support

- **Auteur** : EL MOUKTADIR Mohamed
- **GitHub** : [@elmouktadir](https://github.com/elmouktadir)
- **Dépôt** : [Rapport_PFE_2026-](https://github.com/elmouktadir/Rapport_PFE_2026-)

---

**Année Universitaire : 2025/2026**
