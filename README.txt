Projet d'accidentologie Partie 1 : accidents de véo sur le territoire GPSEA (Grand Paris Sud Est Avenir)

1/ Architecture fichiers
- DOCUMENTS : contient les éléments de documentation des données (dictionnaire, métadonnées etc) au format .pdf ou .xlsx selon le format fourni par le distributeur. Peut contenir également des éléments pour une présentation (Libre office Impress (.odp) ou .pdf).
- DONNEES : contient toutes les données brutes.
- TRAITEMENT : données intermédiaires. Données conservées qui permettent d'avoir une donnée à un instant du traitement.
- RESULTATS : contient les données finies, après traitement, dans un format exploitable pour le SIG ou un tableur. Peut contenir également des images (cartes, graphiques etc) utiles pour une présentation du projet.
- Les notebooks python sont gardés dans l'espace principal car ils doivent accéder rapidement aux différentes données/productions.

2/ Les notebooks
Pour exécuter les notebooks dans de bonnes conditions, veuillez exécuter :
- pour eda_1.ipynb, carto.ipynb et cyclo.ipynb requirements_cyclo.txt
