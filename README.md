<h1 style="text-align: center; font-size: 35px;">Anticipation des besoins énergétiques de bâtiments</h1>

## Description
Taille du jeu de données : **1,2 Mo** <br>
Le jeu de données se trouve dans le dossier `data/`

### Procédure
- Exploration des données
- Nettoyage des données
- Séparation des cibles 
- Analyse des données
- Modélisations
- Sélection des modèles
- Analyse de l'impact des features avec SHAP


### Dossiers & fichiers
- **graphiques** &rarr; Dossier contenant les graphiques enregistrés au cours de l'analyse.
- **data** &rarr; Dossier contenant les données ainsi que les dataframes enregistrés au format .csv au cours du projet.
- **notebook_eda.ipynb** &rarr; Notebook comportant l'analyse exploratoire des données.
- **notebook_modelisation_1.ipynb** &rarr; Notebook comportant la modélisation de la première cible : **SiteEnergyUse(kBtu)**.
- **notebook_modelisation_2.ipynb** &rarr; Notebook comportant la modélisation de la seconde cible : **TotalGHGEmissions**.
- **presentation_slides.pdf** &rarr; Fichier pdf des slides de présentation de l'analyse exploratoire utilisées à lors de la soutenance du projet.
- **requirements.txt** &rarr; Fichier texte contenant la liste des bibliothèques utilisées

## Installation
Pour une utilisation en local :

```bash
git clone https://github.com/amaysounabe/ocr-p4.git
cd ocr-p3
pip install -r requirements.txt
```