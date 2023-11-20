![logo](https://github.com/CelineBoutinon/faux-billets/assets/143210563/c6b645d3-3ced-4b28-839f-e28d95f56e34)



# DETECTER DES FAUX BILLETS AVEC PYTHON

Projet realisé en juin 2023 dans le cadre de ma formation Data Analyst avec OpenClassrooms.

## Objectif du projet

L’ONCFM (Organisation Nationale de lutte Contre le Faux Monnayage) est une organisation publique ayant pour objectif de mettre en place des méthodes d’identification des contrefaçons des billets en euros. Dans le cadre de cette lutte, elle souhaite mettre en place un algorithme qui soit capable de différencier automatiquement les vrais des faux billets à partir des caractéristiques
géométriques de ces billet.

L’algorithme devra être capable de prendre en entrée un fichier contenant les dimensions de plusieurs billets,
et de déterminer le type de chacun d’entre eux, à partir des seules dimensions. Le format type de fichiers de
billets avec lequel l’algorithme est censé fonctionner est fourni dans le fichier nommé billets_production.csv, qui comporte les caractéristiques géométriques de 1 500 de billets dont 1 000 sont vrais et 500 sont faux.

La modélisation devra mettre en concurrence deux méthodes de prédiction, une régression logistique classique et un k-means, duquel seront utilisés les centroïdes pour réaliser la prédiction. L'algorithme se devra d’être le plus performant possible pour identifier un maximum de faux billets au sein de la masse de billets analysés chaque jour et une analyse des nombres de faux positifs et faux négatifs via une matrice de confusion devra etre faite. Enfin, le compte-rendu de la mission devra présenter les traitements et analyses réalisés en amont, les différentes pistes explorées pour la construction de l’algorithme et le modèle final retenu.


## Liste des dossiers & fichiers

* **dossiers :**
  - **donnees-brutes :** fichiers téléchargés depuis les sources (format .csv) 
  - **donnees-nettoyees :** fichier de données retraité (format .csv) avec notebook_1.ipynb prêt à uploader pour les analyses dans les 3 autres notebooks
 
* **fichiers :**
	- **notebook_1.ipynb :** code Python permettant l'import des fichiers .xlsx, leur nettoyage et effectuant la régression linéaire pour combler les donnees manquantes
	- **notebook_2.ipynb :** code Python pour l'ACP et le k-means
	- **notebook_3.ipynb :** code Python pour la régression logistique
	- **notebook_4.ipynb :** code Python pour le détecteur final de faux billets
	- **BILLETS_TEST.csv :** jeu de test pour le détecteur final
	- **presentation.pdf:** diapositives de présentation du projet
  - **presentation_notes.pdf :** notes d’accompagnement des diapositives de présentation du projet
  - **functions.py :** fichier de fonctions auxquelles les notebooks Jupyter font appel


## Compétences développées
* Réaliser une régression logistique
* Opérer des classifications automatiques pour partitionner les données
* Réaliser une analyse prédictive
* Réaliser une régression linéaire


## Langages & software

* Python 3.9.13
  * matplotlib 3.6.2
  * missingno 0.5.1
  * numpy 1.24.1
  * pandas 1.5.2
  * plotly 5.14.1
  * scikit-learn 1.2.2
  * scipy 1.10.0
  * seaborn 0.12.2
  * statsmodels 0.13.5
 

* Jupyter Notebook 6.4.12








