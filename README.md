# MLOps_With_LineaPy
Data Science Workflow with LineaPy

**LineaPy Data Science : Le MLOps devient SIMPLE!!**

D'après la documentation officiel de LineaPy, elle définie par :

LineaPy est un package Python pour la capture, l’analyse et l’automatisation des flux de travail de science des données. À un niveau élevé, LineaPy trace la séquence d’exécution du code pour former une compréhension complète du code et de son contexte. Cette compréhension permet à LineaPy de fournir un ensemble d’outils qui aident les scientifiques des données à mettre leur travail en production plus rapidement et plus facilement, avec seulement deux lignes de code

### Pourquoi avons-nous besoin de LineaPy ?

Le processus de développement de la science des données vers la production est un processus d'ingénierie complexe. 

Selon un article de VentureBeat, environ 90 % des projets de science des données ne parviennent pas à la production. En bref, seul un projet sur dix parvient à la production. Il est facile d'écrire un code désordonné dans Jupyter puisque vous allez faire beaucoup d'EDA (Exploratory Data Analysis), d'analyses statistiques, d'édition des cellules, de suppression des cellules, etc. En outre, le maintien de la propreté et de l'ordre du Jupyter prend du temps et nécessite beaucoup d'efforts. Le refactoring du code de développement de la science des données et la construction des pipelines sont complexes, manuels et prennent beaucoup de temps. LineaPy fournit seulement deux lignes de code pour transformer le code de développement en code de production et générer le pipeline requis.


### Concepts:

   1) L'artefact fait référence à un résultat intermédiaire dans le processus de développement de la science des données.
   2) Dans le flux de travail de la science des données, un artefact peut être un modèle, un graphique, une statistique, un cadre de données ou une fonction        caractéristique.
   3) LineaPy traite l'artefact comme un code et une valeur. Il stocke la valeur de l'artefact et également le code nécessaire pour dériver l'artefact.
### Magasin d'artefacts :

   1) Les artefacts sont stockés dans le magasin d'artefacts.
   2) Le magasin d'artefacts enregistre également les métadonnées de l'artefact, comme l'heure de création et la version, etc.
   3) Le magasin d'artefacts est globalement accessible par tous. L'utilisateur peut visualiser, charger et construire sur les artefacts à travers différentes sessions de développement et même différents projets.


### Pipeline :

   1) Un pipeline fait référence à une série d'étapes qui transforment les données en informations/produits utiles.
   2) Ces pipelines sont développés composant par composant, puis plus tard tous les composants sont connectés pour obtenir le pipeline complet.
   3) Dans LineaPy, chaque composant est représenté comme un artefact, et LineaPy fournit des API pour créer des pipelines à partir d'un groupe d'artefacts.
