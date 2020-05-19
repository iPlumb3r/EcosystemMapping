Mise en contexte
==
Dans le contexte d'E2M on a :
* Question = "Qui ?"
* Précision = Qui est impliqué ? Qui agit ?
* Concept intentionnel correspondant : @Agent (https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Agent.md)

Ce concept incarne une cible dont le rôle peut être joué par un série de concept extensionnels que sont :

Classiquement :
* §Person : Un individu particulier
* §Organization : Un ensemble de §Person ou d'§Organization   

Mais potentiellement ce peut tout aussi bien être l'un ou l'autre des concepts suivants :
* §Projet : Initiative particulière d'une §Person ou d'une §Organization
* §Software : Produit de type logiciel (ex : une instance d'IA qui réalise des taxonomies)
* §Product : Produit de type matériel (ex : une voiture "taxi" autonome qui propose des courses)
* Ou bien autre chose encore à laquelle je n'ai pas pensé ...

Conséquence
==
Il n'y a donc PAS d'un côté des ITEMS/Individus qui soient des @Agent et de l'autre des ITEMS/Individus qui soient des §Person (ou des §Organization ou autre) ...   
... mais bien des ITEMS/Individus qui sont SIMULTANEMENT des @Agent ET des §Person (ou des §Organization ou autre)

Avantages
==
Cela permet de mieux gérer les caractéristiques et les relations relevant de chaque Concept, car chaque ITEM/Individu peut être vue :
* soit par rapport "à ce qu'il fait" (=> en tant que @Agent)
* soit par rapport "à ce qu'il est" (=> en tant que §Person ou §Organization, voire §Project ou §Product)

Exemple
==
Ainsi dans le cadre d'un écosystème relatif à l'économie circulaire, on peut imaginer que : 
* chaque @Agent soit caractérisé par un "re-use ratio" (correspondante son taux de recyclage)
* chaque §Person soit caractérisé par une "birth date" 
* chaque §Organization soit caractérisé par une  "size" (correspondant aux nb de ces membres)

Dans ce contexte, on aura alors :
* L'ITEM/Individu "John Doe" qui appartiendra simultanément aux TYPES/Classes §Person ET @Agent (et sera donc caractérisé par un "re-use ratio" ET une "birth date")
* L'ITEM/Individu "RecycleAll" qui appartiendra simultanément aux TYPES/Classes §Organization ET @Agent  (et sera donc caractérisé par un "re-use ratio" ET une "size")
