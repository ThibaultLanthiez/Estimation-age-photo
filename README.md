[:arrow_left: Retour vers le portfolio](https://github.com/ThibaultLanthiez/Portfolio)

<img src="https://github.com/ThibaultLanthiez/Estimation-age-photo/blob/main/image-data.PNG" width="100%" and height="80%"/>

# Estimation de l'âge d'une personne sur une photo

L'objectif est déterminer l'âge d'une personne d'après une photo de son visage.

Pour cela, j'ai téléchargé sur la plateforme Kaggle un dataset de 20 000 photos de personnes annotées de leur âge.

Avec le langage python, j'ai pu faire de l'augmentation d'images (data augmentation) en faisant par exemple subir des rotations et des zooms aux images. Cela permet d'augmenter le nombre d'images pour réduire le risque de sur-apprentissage. 

Ensuite, j'ai divisé ces images en jeux de d'apprentissage, de validation et de test.

Enfin, j'ai créé un réseau de neurones à convolution (CNN) avec la bibliothèque Tensorflow.Keras.

Je pense que mon modèle est améliorable. Il fait une erreur absolue moyenne de 11 ans dans la prédiction de l'âge de la personne sur les photos.

# Code

Voici le code du projet : [notebook](https://github.com/ThibaultLanthiez/Estimation-age-photo/blob/main/Age%20estimation.ipynb)
