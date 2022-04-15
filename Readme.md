# Projet machine learning : dataset bank marketing

Par :
- MAFTOUL Omar
- MAREGA Oumar
- MAR Ndeye
- MEBARKI Mehdi

### Contexte
Le but de ce projet est de determiner si un client va suscrire ou pas pour un dépot à terme au sein d'une banque.
Pour cela nous allons les algorithmes de machine learning suivant : 
- KNN
- KMeans
- Decision tree
- Random forest
### Jeu de données

https://www.kaggle.com/datasets/yufengsui/portuguese-bank-marketing-data-set?select=bank-full.csv

## Configuration

### Configurer le virtualenv si nécessaire
    
La configuration d'un [virtualenv](https://virtualenv.pypa.io/en/stable/) est optionelle. Elle est recommendée si vous utilisez un IDE tel que PyCharm par exemple, afin de mieux isoler les dépendances entre celles du projet et de votre système. 
```sh
# création de l'environnement virtuel
python3 -m venv ./venv #(sur Linux / Mac)
python3 -m venv .\venv #(Sur Windows)
# activation de l'environnement
.\venv\Scripts\Activate.ps1 # (Si vous êtes sur powershell)
.\venv\Scripts\Activate.bat # (Sur tout autre shell windows)
source ./venv/bin/activate # (Linux/Mac) 
```

### Récupération du projet

```sh
git clone git@github.com:OUMAREGA/ml-bank-full.git
cd ml-bank-full
```

### Installation des dépendances
[pip](https://pypi.python.org/pypi/pip) est le gestionnaire de dépendances qui
va nous permettre d'installer tout ce qui est nécessaire à ce projet.

Cette étape **n'est nécessaire que si** vous souhaitez éditer notre projet, ou démarrer notre IHM Streamlit.

Il faut exécuter la commande suivante dans le dossier `news` (de préférence sous un virtualenv) :

`pip install -r requirements.txt`

### Jupyter Notebooks

Dans un terminal à partir du répertoire racine du projet, exécutez la commande

```
jupyter notebook
```
ou
```
python -m jupyter notebook
```