Pourquoi un modèle à 2 niveaux ?
==

Généralités
-
La cartographie d'un __écosystème__ consiste essentiellement à identifier __"QUI ? fait QUOI ?, COMMENT ? Pour QUOI ? et POURQUOI ?"__

La réponse à chacune de ces questions peut avantageusement être apportée via un __modèle "à 2 niveaux"__ :
* Un 1er niveau qui fait appel à des concepts __"Intentionels"__ (relatifs à la __finalité__ de la chose)
* Un 2nd niveau qui fait appel à des concepts __"Extensionels"__ (relatifs à la __nature__ de la chose)

Modèle simplifié :
![Basic Model](https://github.com/iPlumb3r/EcosystemMapping/blob/master/images/ConceptualModel%40E2M_2020-03-04.png)


Par exemple, la réponse à la question "QUI ?"   
est apportée au 1er niveau par le concept __intentionel__ #Agent (= "la chose qui agit (quelque soit sa nature)")
puis elle complétée au 2nd niveau par différents concepts __extensionels__   
Classiquement il peut s'agir des concepts suivants :
* #Person : Un individu particulier   
* #Organization : Un ensemble de #Person ou d'#Organization   
Mais potentielement ce peut tout aussi bien être l'un ou l'autre des concepts suivants : 
* #Projet : Initiative particulière d'une #Person ou d'une #Organization  
* #Software : Produit de type logiciel (ex : une instance d'IA qui réalise des taxonomies)   
* #Product : Produit de type matériel (ex : une voiture "taxi" autonome qui propose des courses)   

La réponse à la question  "QUOI ?"    
est répondu au 1er niveau par le concept __intentionel__ #Deliverable (="la chose qui est livrée/développée/spécifiée (indépendament de sa nature)"
puis est complété au 2nd niveau par différents concepts __extentionels__ qui prennent en compte "la nature de la chose" (à un niveau plus ou moins détaillé en fonction du besoin) : #Product, #Service, ... 

Une "mécanique" similaire s'applique pour la réponse aux autres questions ...

Avantages
-
Cette approche à 2 niveaux présente l'avantage de pouvoir définir un modèle intentionel "orthogonal" (= indépendant) au modèle extensionel.

Cela permet de se doter d'un modèle générique de description d'écosystème qu'il est possible de spécialiser en fonction du type d'écosystème que l'on souhaite cartographier.

Remarque : Remarque le modèle extensionel lui-même peut disposer d'un certain niveau de généricité s'il est possible de gérer sous forme de taxonomies les différents concepts potentiellement candidats à être des classes de l'ontologie.    
Exemple : #Product hasType #ProductType (Software, Hardware, ...)   
=> Cette possibilité dépends du besoin (ou pas) de gérer des relations particulières entre ces concepts

Annexe(s)
-
Proposition de modèle intentionel "générique" 

![Intentional Model](https://github.com/iPlumb3r/EntangledBootstrap/blob/master/images/IntentionalModel_2020-02-16.png)

Cas d'usage (simplifié) relatif au projet lui-même
![EBR Use Case](https://github.com/iPlumb3r/EntangledBootstrap/blob/master/images/UseCase_EBR-itself_2020-02-15.png)
