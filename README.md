# Q_learning-Model

## Définitions:
### Qu'est ce que le reinforcement learning ?
    Le reinforcement learning est une méthode de machine learning dont l’objectif est de permettre
    à un agent (entité virtuelle : robot, programme, etc.), placé dans un environnement interactif 
    (ses actions modifient l’état de l’environnement), de choisir des actions maximisant des récompenses 
    quantitatives. L’agent fait des essais et améliore sa stratégie d’action en fonction des récompenses 
    fournies par l’environnement.

### Qu'est-ce que le Q-learning ?
    Il existe de nombreux algorithmes de reinforcement learning catégorisés en plusieurs sous-familles.
    Le Q-learning est à la fois relativement simple et permet en même temps de comprendre des mécanismes 
    d’apprentissage communs à beaucoup d’autres modèles.
    
Pour illustrer de manière introductive, un algorithme de Q-learning fonctionne pour résoudre un problème basique. Par exemple, dans le jeu du labyrinthe, l’objectif du jeu est d’apprendre au robot à sortir du labyrinthe le plus rapidement possible alors qu’il est placé aléatoirement sur l’une des cases blanches. Pour cela, il y a trois étapes centrales dans le processus d’apprentissage :

    1. Connaitre : définir une fonction action-valeur Q ;
    2. Renforcer ses connaissances : mettre à jour la fonction Q ;
    3. Agir : adopter une stratégie d’actions PI
    
Ainsi, le Q-learning est un algorithme d’apprentissage par renforcement qui cherche à trouver la meilleure 
action à entreprendre compte tenu de l’état actuel. Il est considéré comme hors politique parce que la fonction 
de Q-learning apprend des actions qui sont en dehors de la politique actuelle, comme prendre des actions aléatoires, 
et donc une politique n’est pas nécessaire. Plus précisément, le Q-learning cherche à apprendre une politique qui maximise la récompense totale.

pour plus de détails veuillez trouvez ci joint une présentation détaillée où on explique la fonction de q-learning qui maximise la récompense.

[Cliquez Ici !](https://github.com/Simo1Goat/Q_learning-Model/blob/4ada0961c6dd0c76198f352fd1a47df5cdaa95ea/Q-learning%20Presentation.pdf)

pour mieux comprendre cet algorithme vous allez trouver le code Python sur l'entrepôt et les manutentions.

[Cliquer Ici !](https://github.com/Simo1Goat/Q_learning-Model/blob/4ada0961c6dd0c76198f352fd1a47df5cdaa95ea/Q-learning%20model.ipynb)
