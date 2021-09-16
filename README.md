# Twitter_Deep_learning - Disaster tweet prediction

Ici nous traitons un problème de classification binaire de texte au moyen de réseau de neurones.

Nous avons traité le texte au moyen de techniques de tokenisation et de vectorisation.

Puis nous avons testé deux variantes de réseaux de neurones: 
    - un réseau composé d'une couche d'embedding, puis de deux recurrent neural networks de type GRU suivi de deux couches Dense.
    - un réseau composé d'une couche d'embedding préentrainée (https://tfhub.dev/google/tf2-preview/gnews-swivel-20dim/1) suivi également de      deux couches Dense.
    
Ce projet faisait partie d'une compétition Kaggle. Nos deux modèles ont tous les deux atteints un F1 score de plus de 0.75 (les données d'entrainement avaient une distribution de la cible de 0: 0.57/ 1: 0.43)
