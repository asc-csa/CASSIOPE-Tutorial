<p align="center">
   <img src="https://www.asc-csa.gc.ca/images/satellites/cassiope_logo.jpg" alt="CASSIOPE logo"> 
   <br> Crédit d'image | Image credit: <a href=https://www.asc-csa.gc.ca/images/satellites/cassiope_logo.jpg>ASC-CSA</a>
</p>

<p align="center">
    <a href="#stars">
        <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="#watchers">
        <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial/commits/main">
        <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="https://github.com/asc-csa/EO-Visualization-and-Search-Tutorial/graphs/contributors">
        <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/CASSIOPE-Tutorial">
    </a>
    <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
        <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
    </a>
</p>

<h2 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h2>

<a id="titre-du-projet"></a>
# Tutoriel pour les données du satellite CASSIOPE

<!-- A short summary phrase for the project (required)-->
> **Description brève :**
> Ce tutoriel présente comment explorer et visualiser les données du satellite canadien CASSIOPE
---

## À propos
Le satellite canadien CASSIOPE (**CAS**cade, **S**mallsat and **IO**nospheric **P**olar **E**xplore), exploité par l'université de Calgary, est composé de la suite d'instruments scientifiques e-POP (Enhanced Polar Outflow Probe) pour étudier l'ionosphère, où l'espace rencontre la haute atmosphère. Ces instruments recueillent des données sur les effets des tempêtes solaires et, plus particulièrement, sur leur impact néfaste sur les communications radio, la navigation par satellite et d'autres technologies spatiales et terrestres. Pour en apprendre plus sur les instruments sur CASSIOPE, vous pouvez consulter une table résumée [ici](https://epop.phys.ucalgary.ca/payload/).

Ce tutoriel aide à mieux comprendre, extraire et visualiser les données du satellite CASSIOPE, plus spécifiquement celles de l'instrument Fast Auroral Imager (FAI). Les données visualisées dans ce tutoriel sont utilisées avec l'autorisation de l'Université de Calgary. Les scripts sont en Python3. Pour en savoir plus sur CASSIOPE, consultez [la page officielle](https://epop.phys.ucalgary.ca/).

---

## Prérequis

- Assurez-vous d'installer les bibliothèques nécessaires à faire fonctionner le tutoriel.

---

## Démarrage rapide
 📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```
---

## Fonctionnalités

- 01-Extraire-Données.ipynb explique les deux plateformes d'extraction de données de l'Université de Calgary.
- 02-Exemple-FAI.ipynb est un script Python3 pour visualiser les données de l'instrument FAI à titre d'exemple
- 03-Vidéo-FAI.ipynb est un script Python3 pour créer une vidéo d'images du FAI.
- 04-Projection-Cartographique-FAI.ipynb est un script Python3 pour visualiser une image du FAI picture avec différentes projections cartographiques.
- 05-Disponibilité-Données.ipynb est un script Python3 pour visualiser la disponibilité des données par dates et instruments.

## Structure du projet

```text
├── requirements.txt
├── Français                              # Version Français du tutoriel
    ├── Jupyter Notebooks
├── English                               # Version Anglais du tutoriel
    ├── Jupyter Notebooks
```

## Licence

Ce projet est  sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/CASSIOPE-Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h2 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h2>

<a id="project-title"></a>
# CASSIOPE Satellite Data Tutorial

> **Brief description:**
> This tutorial shows how to explore and visualize data from the Canadian CASSIOPE satellite.

## About
The Canadian CASSIOPE satellite (**CAS**cade, **S**mallsat and **IO**nospheric **P**olar **E**xplore), operated by the University of Calgary, carries the Enhanced Polar Outflow Probe (e-POP) suite of scientific instruments to study the ionosphere, where space meets the upper atmosphere. The instruments collect data about the effects of solar storms and, more specifically, their harmful impact on radio communications, satellite navigation and other space and ground-based technologies. To know more about the instruments on CASSIOPE, you can consult a summary table [here](https://epop.phys.ucalgary.ca/payload/).

This tutorial helps to better understand, extract and visualize CASSIOPE satellite data, specifically from the Fast Auroral Imager (FAI) instrument. The data visualized in this tutorial is used with the permission of the University of Calgary. The scripts are in Python3. To know more about CASSIOPE, visit the [official web page](https://epop.phys.ucalgary.ca/). 


## Prerequisites
- Make sure to install the requirements for the tutorial.
  
## Quick Start
   
📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## Features

- 01-Extract-data.ipynb explains the two data extraction platforms of the University of Calgary.
- 02-FAI-example.ipynb is a Python3 script for visualizing data from the FAI instrument as an example of what we can do.
- 03-FAI-Video.ipynb is a Python3 script to create a video of FAI pictures.
- 04-FAI-Map-Projection.ipynb is a Python3 script for visualizing FAI picture with different map projections.
- 05-Data-Availability.ipynb is a Python3 script for visualizing the availability of the data per dates and instruments.

## Project Structure

```text
├── requirements.txt
├── Français                              # Version Français du tutoriel
    ├── Jupyter Notebooks
├── English                               # Version Anglais du tutoriel
    ├── Jupyter Notebooks
```

## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/CASSIOPE-Tutorial/blob/main/LICENSE.txt) file for details.

---
