Introduction
==
Pour exploiter au mieux l'ontologie E2M il est crucial de bien comprendre __les tenants et les aboutissants__ de la dichotomie "Intention VS Extension" : 
* Qu’est-ce que c’est ?
* A quoi ça sert ?
* Quels en sont les avantages ?
* Comment ça marche ?
* Pourquoi l'approche "classique" ne peux pas marcher !

Contexte
==
La dichotomie "Intention VS Extension" est une technique de modélisation qui a été développé suite au constat de la difficulté à faire émerger un "tronc commun" entre différentes cartographies d’écosystème alors même qu’il aurait été tout à fait logique de pouvoir en faire émerger un !
> exemples : PAIR, Petit Débrouillards, Alternatiba, DFC, dWeb x SW …

La raison en est que tous les modèles de ces cartographies d’écosystème sont « monolithiques » au sens où chaque ITEM/Individu de la carte ne peux appartenir qu’à 1 et 1 seul TYPE/Classe ...   
... et chaque modèle doit "jongler" avec des TYPES/Classes qui ne sont pas très homogènes entre-eux !

En effet, parfois les TYPES/Classes utilisés sont :
* Orientés par rapport au "rôle joué"» (=> Ce qu’ils "FONT"). Exemples : "Client", "Produit Fourni"
Ou bien
* Orientés par rapport à leur "nature" (=> Ce qu’il "SONT") : Exemples : "Organisation", "Logiciel"

Et cela pose un problème car un ITEM/Individu donné peut être "en même temps" : 
* un "Client" ET une "Organisation" 
OU
* un "Client" ET une "Personne"

De la même manière, un ITEM/Individu donné peut être "en même temps" : 
* un "Produit Fourni" ET "Logiciel" 
OU
* un "Produit Spécifié" ET un "Logiciel"

Par conséquent, on se trouve « de facto » dans une situation ou la modélisation basée sur du MONO-TYPE touche à ses limites.
Il nous faut un nouveau paradigme de modélisation plus souple, plus expressif, ...
> En bref, qui "colle" mieux à la réalité du terrain !

C’est là qu’intervient la dichotomie "Intention VS Extension".

Qu'est-ce que c'est ?
==
La dichotomie "Intention VS Extension" est une technique de modélisation.    
Elle s'appuie sur le principe de "Separation Of Concerns" appliqué dans le contexte d'une cartographie d'écosystème.   
En effet, dans ce contexte les CHOSES indentifées dans la cartographie ont 2 ASPECTS différents et complémentaires : 
* L'un étant lié à ce qu'elles "FONT"
* L'autre étant lié à ce qu'elles "SONT"

__Remarque__:
S’il n’y avait qu’une seule chose à retenir ça serait que :
Il n’y a PAS des ITEMS/Individus intentionnels ET des ITEMS/individus extensionnels …
… MAIS UNIQUEMENT des ITEMS/Individus qui ont un ASPECT intentionnel ET un ASPECT extensionnel

De ce fait, les modèles intentionnel et extensionnels sont des modèles ORTHOGONAUX qui accueille les PROJECTIONS des ASPECTS correspondants ...   
... et qui permettent de gérer les caractéristiques et les relations qui sont propre à chaque ASPECT.

A quoi ça sert ?
==

Quels en sont les avantages ?
==
Les principaux avantages de la dichomie "Intention VS Extention" sont les suivants :
* Permet de rationaliser la gestion des propriétés et des relations
* Permet d'éviter l'explosion combinatoire des classe à gérer (En particulier pour "Deliverable")
* Permet de faciliter le passage de l'informel au formel (En particulier pour "Market" et "Finality")


Comment ça marche ?
==

Ressources
==

Un cas d'usage emblématique : https://github.com/iPlumb3r/EcosystemMapping/blob/master/0_UseCases/Bob_develops_SmartphoneCase_FR.md   
Un article sur les Invariants Métiers : https://www.linkedin.com/pulse/les-invariants-m%C3%A9tiers-du-plm-bernard-chabot/
