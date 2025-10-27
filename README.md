# bastien06150-bastien06150

#  Bonjour, je suis Maingaud Bastien !

 Développeur Python passionné par les algorithmes, la data et la finance.

Mon objectif : concevoir des solutions **claires, performantes et documentées** pour résoudre des problèmes réels.
Ce portfolio regroupe mes projets réalisés dans le cadre du parcours OpenClassrooms et en autonomie.

---

##  Mes principaux projets

| Projet | Description | Technologies | Lien |
|---------|--------------|---------------|------|
| **Projet 1 – Analyse de marché** | Développement d’un programme Python automatisé pour extraire les prix des livres d’occasion à partir du site *Books to Scrape*. | Python, Pandas, Matplotlib | [Voir le repo](https://github.com/bastien06150/books-To-Scrape) |
| **Projet 2 – AlgoInvest & Trade** | Algorithme d’optimisation d’investissement avec 500 € (force brute, glouton, DP). | Python, CSV, Pandas, Pptx | [Voir le repo](https://github.com/bastien06150/projet_echec) |
| **Projet 3 – Classification clients** | Segmentation marketing via clustering K-Means et PCA. | Scikit-learn, Pandas, Seaborn | [Voir le repo](https://github.com/bastien06150/projet-justStreamIt) |
| **Projet 4 – Tableau de bord interactif** | Dashboard d’analyse avec Streamlit. | Streamlit, Plotly, Python | [Voir le repo](https://github.com/bastien06150/HomeSkolar-) |
| **Projet 5 – AlgoInvest & Trade** | Algorithme d’optimisation d’investissement avec 500 € (force brute, glouton, DP). | Python, CSV, Pandas, Pptx | [Voir le repo](https://github.com/bastien06150/algorithme-en-python) |
---

##  Compétences techniques

- **Langages** : Python, SQL, HTML/CSS
- **Librairies** : Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Outils** : Git, VS Code, Jupyter Notebook, Power BI
- **Concepts clés** : 
  - Optimisation algorithmique (Knapsack, Brute-force, Greedy)
  - Analyse et visualisation de données
  - Machine Learning supervisé et non supervisé
  - Automatisation de scripts

---

##  Focus : Projet 7 – AlgoInvest & Trade

###  Objectif :
Concevoir un programme Python qui maximise le **profit d’un portefeuille d’actions** sur 2 ans sous contrainte de **budget (500 €)**.

###  Méthodes développées :
- Force brute : test de toutes les combinaisons possibles (O(2ⁿ))
- Programmation dynamique (Knapsack 0/1) : optimum exact en O(N·W)
- Approche gloutonne : tri des actions et sélection rapide en O(N log N)

###  Résultats :
| Méthode | Temps d’exécution | Profit (€) | ROI (%) |
|----------|------------------|-------------|----------|
| Brute-force | 1.45 s | 196.6 | 39.4 % |
| Gloutonne | < 0.01 s | 198.5 | 39.7 % |
| DP Knapsack | < 1 s | 198.5 | 39.7 % |

L’algorithme optimisé retrouve le même profit maximal que la force brute mais en un temps **100× plus rapide**.

###  Détails :
- Lecture automatisée de fichiers CSV (`dataset1` et `dataset2`)
- Comparaison avec les portefeuilles de Sienna
- Rapport PowerPoint et Google Slides générés par code

###  Fichiers principaux :
- `optimized.py` → version gloutonne et dynamique
- `bruteforce.py` → version exhaustive
- `datasets/` → données d’entrée
- `AlgoInvest_Presentation_Complete_Comparaison_Final.pptx` → rapport complet

---

##  Exemple de résultats visuels
*(capture d’écran de tes graphiques ou extraits de résultats)*
![Aperçu du projet AlgoInvest](images/algo_invest_preview.png)

---

##  Me contacter

 **Email** : bastienmaingaud@gmail.com   
 **GitHub** : github.com/bastien06150  

---
