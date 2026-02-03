# Introduction aux notebooks Jupyter

Ce dépôt contient les supports pour le cours d'introduction aux notebooks Jupyter.


## Travail à effectuer en amont de la séance de travaux pratiques

En amont de la séance de travaux pratiques, vous devez lire les 4 notebooks suivants :

* **Introduction aux notebooks Jupyter** ([Jupyter notebook](/notebooks/Introduction%20aux%20notebooks%20Jupyter.ipynb), [HTML](/html/Introduction%20aux%20notebooks%20Jupyter.html))
* **Introduction à NumPy** ([Jupyter notebook](/notebooks/Introduction%20à%20NumPy.ipynb), [HTML](/html/Introduction%20à%20NumPy.html))
* **Introduction à Matplotlib** ([Jupyter notebook](/notebooks/Introduction%20à%20Matplotlib.ipynb), [HTML](/html/Introduction%20à%20Matplotlib.html))
* **Introduction à pandas** ([Jupyter notebook](/notebooks/Introduction%20à%20pandas.ipynb), [HTML](/html/Introduction%20à%20pandas.html))


## Création de votre dépôt GitHub

Connectez-vous sur GitHub, cliquez sur *Use this template* (en haut à droite) et créer votre dépôt.
C'est ce dépôt que vous clonerez ensuite (sur Onyxia ou en local).


## Travailler sur des notebooks Jupyter

Bien que de nombreux environnements de développement intégré permettent de travailler sur des notebooks Jupyter, notamment Visual Studio Code, nous utiliserons ici [JupyterLab](https://jupyterlab.readthedocs.io).

### Travailler sur Onyxia

* GitHub : Créez votre dépôt à partir de celui-ci (*Use this template*) si ce n'est pas déjà fait.
* Datalab : Lancez un service Jupyer-python
  * Dans l'onglet Git, coller l'adresse https de votre dépôt

Le service se lance et le clone est automatiquement créé.
Vous n'avez normalement pas besoin d'installer de paquets Python, les paquets nécessaires étant déjà installés.
Sinon, si vous avez une erreur lors d'un import :

* Ouvrez un terminal (*File > New > Terminal*)
* Allez dans votre dépôt (`cd ...`) puis exécutez la commande suivante : `pip install -r requirements.txt`


### Travailler en local sur votre ordinateur portable

Pour effectuer ces travaux pratiques en local sur votre ordinateur portable, il vous faudra :

* installer JupyerLab (voir les [instructions](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)),
* installer les paquets Python suivants : `matplotlib` `numpy`, `pandas`, `scikit-learn` et `scipy` : `pip install matplotlib numpy pandas scikit-learn scipy`
* créer votre dépôt à partir de celui-ci (*Use this template*) puis cloner votre dépôt sur votre ordinateur portable,
* lancer JupyterLab (voir les [instructions](https://jupyterlab.readthedocs.io/en/stable/getting_started/starting.html)), et
* aller dans votre dépôt.


### Travail pendant la séances de travaux pratiques.

Il y a quatre notebooks (dans le dossier `notebooks`) dont le nom commence par `Exercices` : deux sujets (un sur NumPy, un sur pandas) et leurs corrections.
Vous travaillerez sur les sujets pendant la séance de travaux pratiques.
Si vous rencontrez une difficulté, privilégiez les questions à votre chargé•e de TP plutôt que de lire la correction : vous pourrez la correction chez vous.


### Sauvegarder votre travail

Contrairement à Visual Studio Code, vous n'avez pas d'interface graphique avec les notebooks Jupyter pour la gestion de versions.
Vous allez donc devoir exécuter les commandes git dans le terminal.
Nous ne sauvegarderons que les notebooks Jupyter (et pas les éventuels fichiers téléchargés pour l'exercice sur pandas).

À la racine de votre dépôt, exécutez les commandes suivantes :
* `git add *.ipynb` : elle ajoute tous les fichiers dont les noms se terminent par `.ipynb`, c'est-à-dire les notebooks Jupyter.
* `git commit -m "Mon travail en TP"` : elle enregistre vos modifications dans une nouvelle version locale.
* `git push` : elle envoie votre version locale sur la version distante.
