# Istraživanje skupa podataka "Bach Chorales"
Demonstrirano je istraživanje skupa podataka koji sadrži harmonije i akorde zabeležene u horalima Johana Sebastijana Baha, kreiranjem i poređenjem različitih modela klasifikacije, klasterovanja i pravila pridruživanja.

Podaci koji su korišćeni su preuzeti sa [linka](https://archive.ics.uci.edu/ml/datasets/Bach+Chorales). 

## Metodologija
Izvršena je eksplorativna analiza i vizuelizacija podataka koristeći biblioteke [matplotlib](https://matplotlib.org/), [seaborn](https://seaborn.pydata.org/). Nakon toga izvršeno je pretprocesiranje podataka pomoću biblioteka [pandas](https://pandas.pydata.org/) i [scikit-learn](https://scikit-learn.org/stable/). Nakon je skup podataka korišćen za treniranje modela klasifikacije, klasterovanja i pravila pridruživanja. Svaka klasa modela je imala zasebne pretprocesirane podatke.

## Korišćeni algoritmi
### Klasifikacija
1. Stablo odlučivanja ([Decision Tree](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html))
2. Slučajna šuma ([Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html))
3. Kategorički naivni Bajes ([Categorical Naive Bayes](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.CategoricalNB.html))
4. Bernulijev naivni Bajes ([Bernouli Naive Bayes](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.BernoulliNB.html))
### Klasterovanje
1. K sredina ([K-means](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html))
2. Hijerarhijsko klasterovanje ([Agglomerative](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.AgglomerativeClustering.html))
3. DBSCAN ([DBSCAN](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html))
### Pravila pridruživanja (IBM SPSS Modeler)
1. Apriori
2. FP-Growth
