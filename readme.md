- Parser : Construit un dictionnaire de document, cette classe est générale pour tout type de fichier texte.
- IndexerSimple : La méthode ‘indexation’ permet de construit
« l’index », « l’index inverse » et « les liens hypertextes from et to ».
- GridSearch : Cette class permet d’initialiser une grille d’optimisation de paramètres.
- Cross_validation : Cette class permet d’initialiser une validation croisé (KFold).
- IRModel : Contient les modèles vectoriel, de langue, et Okapi_bm25.
- PageRank : Dans la class PageRank.
- EvalIRModel : Pour évaluer une requête/requêtes avec une mesure/mesures.
- Hits : Cette class implémente l’algorithme Hits.
- Search : Pour le serveur ,et pour changer le fichier (cacm ou cisi).


Il faut installé les requierment.txt (pip install -r requierment.txt)
Il est hébergé sur : https://billion-search.github.io/search
Il faut lancer le serveur avec : « python app.py » , avec le fichier app.py fournis
