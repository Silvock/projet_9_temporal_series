# Prédiction de la consommation électrique pour ENERCOOP

##Mise en situation

Vous êtes employé chez Enercoop, société coopérative qui s'est développée grâce à la libéralisation du marché de l’électricité en France. Elle est spécialisée dans les énergies renouvelables.

La plupart de ces énergies renouvelables est cependant intermittente, il est donc difficile de prévoir les capacités de production d'électricité. De plus, la demande en électricité des utilisateurs varie au cours du temps, et dépend de paramètres comme la météo (température, luminosité, etc.) Tout le challenge est de mettre en adéquation l'offre et la demande !

##Les données

Vous téléchargerez les données de consommation d'électricité mensuelles à partir de cette page : http://www.rte-france.com/fr/eco2mix/eco2mix-telechargement

Les données météo que vous utiliserez pour corriger les données de l'effet température sont présentes ici : https://cegibat.grdf.fr/simulateur/calcul-dju
Votre mission

Vous vous concentrerez uniquement sur la prédiction de la demande en électricité.

##Missions

    Corrigez les données de consommation mensuelles de l'effet température (dues au chauffage électrique) en utilisant une régression linéaire.
    Effectuez une désaisonnalisation de la consommation que vous aurez obtenue après correction, grâce aux moyennes mobiles.
    Effectuez une prévision de la consommation (corrigée de l'effet température) sur un an, en utilisant la méthode de Holt Winters (lissage exponentiel) puis la méthode ARMA sur la série temporelle désaisonnalisée.

Pour chaque traitement effectué (correction de l'effet température, désaisonnalisation, etc.), vous présenterez les 2 séries temporelles avant et après traitement, sur un graphique où les deux séries temporelles seront superposées.

## Getting Started (=Avant de commencer)

### Prerequisites (=Pré-requis)

- Installer requirements 
- Visualiser la présentation avec Microsoft Sway

## Arborescense 
Dossier notebook : Contient le programme.
Dossier fichiers_csv : Contient les données utilisées.
Dossier presentation : Contient la présentation pdf et les images associées à cette présentation.

Dossier documents : Contient les ressources utilisées.

## Running

1. Pour réaliser la modélisation, ouvrez le notebook Jupyter (dossier 'notebook')et faites "run all".


## Built With (=Fabriquer avec)

* [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/) - The  web-based application suitable for capturing the whole computation process.
* [R](https://www.r-project.org/) -  R is a free software environment for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows and MacOS.




## Authors

* **Thibault SCHMIT** - *Initial work* - [Silvock](https://github.com/Silvock)



## License

This project is licensed under the GNU GPL 3.0 - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Olivier Yoo - Mentor OpenClassrooms
