# Software Elements for Big Data Analysis 
Course @ ENSAE ParisTech by [Xavier Dupré](http://www.xavierdupre.fr/app/ensae_teaching_cs/helpsphinx3/td_3a.html) and [Xavier Durut](https://www.linkedin.com/in/matthieudurut)

# Projet : Distributed Stochastic Gradient Descent

La factorisation de matrice de faible rang est un problème très important en machine learning et en particulier pour les systèmes de recommendations. Parmi ces systèmes, les plus aboutis sont basés sur l'obtention d’un modèle de quelques facteurs latents permettant d’expliquer en faible dimension les interactions entre clients et produits (ou utilisateurs et films). Dans ce projet, nous avons implémenté une version du Distributed Stochastic Gradient Descent (DSGD) pour la factorisation de matrice de faible rang dans le framework Spark Apache, présentée dans cet [article](https://stanford.edu/~rezab/dao/projects_reports/parthasarathy_tea.pdf). Nous avons ensuite étudié le temps de calcul de cet algorithme pour la factorisation avec différents nombres de facteurs latents.
