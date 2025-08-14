<p align="center">
   <img src="https://www.asc-csa.gc.ca/images/satellites/cassiope_logo.jpg" alt="CASSIOPE logo" height=300>
    <br> Crédit d'image | Image credit: <a href="https://www.asc-csa.gc.ca/images/satellites/cassiope_logo.jpg">ASC-CSA</a>
</p>

<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/CASSIOPE-Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/CASSIOPE-Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

---

<h3 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h3>

---

<a id="titre-du-projet"></a>
# Tutoriel pour les données du satellite CASSIOPE

> **Description brève :**
> Ce tutoriel aide à mieux comprendre, extraire et visualiser les données du satellite CASSIOPE, plus spécifiquement celles de l'instrument Fast Auroral Imager (FAI).

## À propos

**Tutoriel pour les données du satellite CASSIOPE** est un tutoriel Jupyter Notebook qui guide les utilisateurs à travers la compréhension, l'extraction et la visualisation des données du satellite CASSIOPE, spécifiquement de l'instrument Fast Auroral Imager (FAI). Il couvre :

- Extraction de données via les plateformes de l'Université de Calgary
- Visualisation des données de l'instrument FAI
- Création de vidéos à partir d'images du FAI
- Projections cartographiques des données FAI
- Analyse de la disponibilité des données par instruments

Le satellite canadien CASSIOPE (**CAS**cade, **S**mallsat and **IO**nospheric **P**olar **E**xplore), exploité par l'université de Calgary, est composé de la suite d'instruments scientifiques e-POP (Enhanced Polar Outflow Probe) pour étudier l'ionosphère, où l'espace rencontre la haute atmosphère.

*Ce tutoriel est fourni à des fins pédagogiques et expérimentales.*

Pour plus d'informations : [CASSIOPE - Université de Calgary](https://epop.phys.ucalgary.ca/)

## Prérequis

- Python 3.x
- Jupyter Notebook ou Jupyter Lab
- Connexion Internet (pour l'accès aux données CASSIOPE)
- Autorisation d'accès aux données de l'Université de Calgary

## Démarrage rapide

1. 📦 **Cloner le dépôt**
   ```bash
   git clone https://github.com/asc-csa/CASSIOPE-Tutorial.git
   cd CASSIOPE-Tutorial
   ```
2. 🐍 **Créer un environnement**
   ```bash
   # Avec virtualenv
   python -m venv env
   source env/bin/activate

   # Ou avec conda
   conda create -n cassiope_env python=3.8
   conda activate cassiope_env
   ```
3. 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Lancer les tutoriels**
   ```bash
   jupyter notebook
   ```

> **Remarque :** Vous devrez obtenir les autorisations d'accès aux données auprès de l'Université de Calgary.

## Structure du projet

```text
├── 01-Extraire-Données.ipynb          # Plateformes d'extraction de données
├── 02-Exemple-FAI.ipynb               # Visualisation des données FAI
├── 03-Vidéo-FAI.ipynb                 # Création de vidéos FAI
├── 04-Projection-Cartographique-FAI.ipynb  # Projections cartographiques
├── 05-Disponibilité-Données.ipynb     # Disponibilité des données
├── requirements.txt                    # Dépendances Python
└── README.md                          # Ce fichier
```

## Licence

Ce projet est sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/CASSIOPE-Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h3 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h3>

---

<a id="project-title"></a>
# CASSIOPE Satellite Data Tutorial

> **Brief description:**
> This tutorial helps users understand, extract, and visualize data from the CASSIOPE satellite, specifically from the Fast Auroral Imager (FAI) instrument.

## About

**CASSIOPE Satellite Data Tutorial** is a Jupyter Notebook tutorial that guides users through understanding, extracting, and visualizing data from the CASSIOPE satellite, specifically from the Fast Auroral Imager (FAI) instrument. It covers:

- Data extraction via University of Calgary platforms
- Visualization of FAI instrument data
- Creating videos from FAI images
- Cartographic projections of FAI data
- Data availability analysis by instruments

The Canadian CASSIOPE satellite (**CAS**cade, **S**mallsat and **IO**nospheric **P**olar **E**xplore), operated by the University of Calgary, carries the Enhanced Polar Outflow Probe (e-POP) suite of scientific instruments to study the ionosphere, where space meets the upper atmosphere.

*This tutorial is provided for educational and experimental purposes.*

More information: [CASSIOPE - University of Calgary](https://epop.phys.ucalgary.ca/)

## Prerequisites

- Python 3.x
- Jupyter Notebook or Jupyter Lab
- Internet connection (for CASSIOPE data access)
- University of Calgary data access permissions

## Quick Start

1. 📦 **Clone the repo**
   ```bash
   git clone https://github.com/asc-csa/CASSIOPE-Tutorial.git
   cd CASSIOPE-Tutorial
   ```
2. 🐍 **Create environment**
   ```bash
   # Using virtualenv
   python -m venv env
   source env/bin/activate

   # Or using conda
   conda create -n cassiope_env python=3.8
   conda activate cassiope_env
   ```
3. 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. 🚀 **Run the tutorials**
   ```bash
   jupyter notebook
   ```

> **Note:** You will need to obtain data access permissions from the University of Calgary.

## Project Structure

```text
├── 01-Extract-data.ipynb              # Data extraction platforms
├── 02-FAI-example.ipynb               # FAI data visualization
├── 03-FAI-Video.ipynb                 # FAI video creation
├── 04-FAI-Map-Projection.ipynb       # Cartographic projections
├── 05-Data-Availability.ipynb        # Data availability analysis
├── requirements.txt                   # Python dependencies
└── README.md                         # This file
```

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/CASSIOPE-Tutorial/blob/main/LICENSE.txt) file for details.
