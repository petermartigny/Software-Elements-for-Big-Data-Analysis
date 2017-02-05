# Software Elements for Big Data Analysis 
Course @ ENSAE ParisTech by [Xavier Dupré](http://www.xavierdupre.fr/app/ensae_teaching_cs/helpsphinx3/td_3a.html) and [Xavier Durut](https://www.linkedin.com/in/matthieudurut)

# Projet : Distributed Stochastic Gradient Descent

La factorisation de matrice de faible rang est un problème très important en machine learning et en particulier pour les systèmes de recommendations. Parmi ces systèmes, les plus aboutis sont basés sur l'obtention d’un modèle de quelques facteurs latents permettant d’expliquer en faible dimension les interactions entre clients et produits (ou utilisateurs et films). Dans ce projet, nous avons implémenté une version du Distributed Stochastic Gradient Descent (DSGD) pour la factorisation de matrice de faible rang dans le framework Spark Apache, présentée dans cet [article](https://stanford.edu/~rezab/dao/projects_reports/parthasarathy_tea.pdf). Nous avons ensuite étudié le temps de calcul de cet algorithme pour la factorisation avec différents nombres de facteurs latents.

# Dataset : 
Les données utilisées pour ce projet sont un sous-ensemble des données fournies dans le cadre du projet Netflix. Nous avons donc utilisé deux datasets : un dataset de training (training\_ratings.txt) et un dataset de test (test\_ratings.txt). Chaque ligne de ces fichiers représente le rating d'un film par un utilisateur. Les fichiers ont donc le format suivant : movie\_id, user\_id, rating. La base d'apprentissage contient  3 255 352 ratings pour 28 978 utilisateurs et 1821 films différents et la base de test contient 100 478 ratings pour 1701 films et 27 555 utilisateurs différents. 

## Nous avons suivi la méthodologie suivante :

####  - Exploration du jeu de données

####  - Implentation de l'algorithme de Distributed Stochastic Gradient

####  -  Comparaison des temps de calcul de l'algorithme


