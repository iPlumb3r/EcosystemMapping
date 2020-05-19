Mise en contexte
==
Dans le contexte d'E2M on a :
* Question = "Qui ?"
* Précision = Qui agit ? Qui s'implique ?
* Concept intentionnel correspondant : <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Agent.md">@Agent</a>

Ce concept intentionel incarne une cible dont le rôle peut être joué par une série de concept extensionnels que sont :

Classiquement :
* <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Person.md">§Person</a> : Un individu particulier
* <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Organization.md">§Organization</a> : Un ensemble de <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Person.md">§Person</a> ou d'<a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Organization.md">§Organization</a>   

Mais potentiellement ce peut tout aussi bien être l'un ou l'autre des concepts suivants :
* §Projet : Initiative particulière d'une §Person ou d'une §Organization
* §Software : Produit de type logiciel (ex : une instance d'IA qui réalise des taxonomies)
* §Product : Produit de type matériel (ex : une voiture "taxi" autonome qui propose des courses)
* Ou bien autre chose encore à laquelle je n'ai pas pensé ...

Conséquence
==
Il n'y a donc PAS d'un côté des ITEMS/Individus qui soient des <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Agent.md">@Agent</a> et de l'autre des ITEMS/Individus qui soient des <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Person.md">§Person</a> (ou des <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Organization.md">§Organization</a> ou autre) ...   
... MAIS bien des ITEMS/Individus qui sont SIMULTANEMENT des <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Agent.md">@Agent</a> ET des <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Person.md">§Person</a> (ou des <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Organization.md">§Organization</a> ou autre)

Avantages
==
Cela permet de mieux gérer les caractéristiques et les relations relevant de chaque Concept, ...   
... Car chaque ITEM/Individu peut être vue :
* soit par rapport "à ce qu'il fait" (=> en tant que @Agent)
* soit par rapport "à ce qu'il est" (=> en tant que §Person ou §Organization, voire §Project ou §Product)

Exemple
==
Ainsi dans le cadre d'un écosystème relatif à l'économie circulaire, on peut imaginer que : 
* chaque @Agent soit caractérisé par un "re-use ratio" (correspondant à son taux de recyclage)
* chaque §Person soit caractérisée par une "birth date" 
* chaque §Organization soit caractérisée par une  "size" (correspondant aux nb de ces membres)

Dans ce contexte, on aura alors :
* L'ITEM/Individu "John Doe" qui appartiendra simultanément aux TYPES/Classes §Person ET @Agent (et sera donc caractérisé par un "re-use ratio" ET une "birth date")
* L'ITEM/Individu "RecycleAll" qui appartiendra simultanément aux TYPES/Classes §Organization ET @Agent (et sera donc caractérisé par un "re-use ratio" ET une "size")
