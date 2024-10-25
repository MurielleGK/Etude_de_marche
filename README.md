#### Projet effectué dans le cadre de ma formation chez OpenClassrooms
# Analyse de Lancement à l'International pour "La poule qui chante"

<p align="center">
  <img src="https://github.com/MurielleGK/Etude_de_marche/blob/main/data/logo.jpg?raw=true" alt="La poule qui chante" width="300"/>
</p>


## Contexte du Projet

Dans le rôle d'une **data analyste** chez *La poule qui chante*, une entreprise française d'agroalimentaire, j'ai mené une étude pour proposer des groupements de pays cibles pour l'exportation de poulets à l'international. À ce stade, aucun pays ou continent spécifique n'a été sélectionné, et tous les marchés mondiaux sont envisageables. Mon rôle était d'utiliser les données de la FAO (Food and Agriculture Organization) pour effectuer une première analyse exploratoire et de clustering afin d'identifier les marchés potentiels à cibler.

## Objectifs du Projet

1. Effectuer une **analyse exploratoire des données** pour comprendre les caractéristiques alimentaires des différents pays.
2. Réaliser une **classification ascendante hiérarchique (CAH)** pour regrouper les pays selon leurs similarités.
3. Comparer les résultats de la CAH avec un **clustering K-means** pour affiner l'analyse.
4. Visualiser les résultats via un **dendrogramme** et d'autres représentations graphiques.
5. Utiliser une **analyse en composantes principales (ACP)** pour comprendre les relations entre les variables et les groupes de pays.

## Outils

- **Python** pour le traitement des données et le clustering
- **Pandas** pour la manipulation des données
- **Matplotlib** et **Seaborn** pour les visualisations
- **Scikit-learn** pour les méthodes de clustering et l'ACP
- **Jupyter Notebook** pour le développement de l'analyse

## Démarche

1. **Préparation des données** : J'ai commencé par le nettoyage et la transformation des données issues de la FAO afin de les rendre exploitables pour l'analyse.
2. **Analyse exploratoire** : J'ai ensuite exploré les données pour comprendre les principales variables qui influencent la production et la consommation de produits alimentaires dans différents pays.
3. **Clustering** : 
   - **Classification ascendante hiérarchique (CAH)** : J'ai effectué un clustering hiérarchique pour regrouper les pays en fonction de leur disponibilité alimentaire, en générant un dendrogramme pour visualiser les résultats.
   - **K-means** : En complément, j'ai appliqué la méthode des K-means pour identifier les centres des clusters et comparer les résultats avec la CAH.
4. **Analyse en composantes principales (ACP)** : J'ai utilisé une ACP pour réduire la dimensionnalité des données et mieux visualiser les relations entre les pays et les variables alimentaires.

## Résultats Clés

- **Dendrogramme** : La CAH a permis de regrouper les pays en fonction de leurs similarités alimentaires, révélant des tendances régionales intéressantes.
- **K-means** : L'analyse K-means a confirmé certains des clusters identifiés avec la CAH et a permis de mieux comprendre les centroïdes de chaque groupe de pays.
- **ACP** : L'analyse en composantes principales a aidé à mieux visualiser les groupes de pays et les relations entre les variables clés, telles que la disponibilité alimentaire, la consommation et l'importation de produits.

## Conclusion

Cette étude a fourni une première segmentation des pays à cibler pour l'exportation de poulets par *La poule qui chante*. L'utilisation combinée de la CAH et des K-means, ainsi que de l'ACP, a permis d'identifier des marchés prometteurs à explorer dans une étude de marché plus approfondie.

## Livrables

- **Notebook Jupyter** contenant la préparation, le nettoyage, et l’analyse exploratoire des données.
- **Clustering et visualisations** comprenant les dendrogrammes, les clusters K-means, et l'ACP.
- **Présentation** des résultats avec des recommandations sur les pays à cibler.

