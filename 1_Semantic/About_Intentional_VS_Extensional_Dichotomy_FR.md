Introduction
==
Pour exploiter au mieux l'ontologie E2M il est crucial de bien comprendre __les tenants et les aboutissants__ de la dichotomie "Intention VS Extension" : 
* Qu’est-ce que c’est ?
* A quoi ça sert ?
* Quels en sont les avantages ?
* Comment ça marche ?
* Pourquoi l'approche "classique" ne peux pas marcher !

Préambule / Contexte
==
La dichotomie "Intention VS Extension" est une __technique de modélisation__.   
Elle a été développée suite au constat de l'extrème difficulté à faire émerger un _"tronc commun"_ entre différentes cartographies d’écosystème ...   
... alors même qu’il aurait été tout à fait logique d'en voir émerger un !
> exemples : PAIR, Petit Débrouillards, Alternatiba, Data Food Consortium, "dWeb x SW", ...

Après analyse, il s'avère que la raison de cet échec est essentiellement lié au caractère "monolithiques" des modèles qui ont été développés. Monolithique dans le sens où chaque ITEM/Individu de la carte ne peux appartenir qu’à 1 et 1 seul TYPE/Classe et chaque modèle doit "jongler" avec des TYPES/Classes qui ne sont pas très homogènes entre-eux car relevant de logique diamétralement opposées (MAIS totalement complémentaires).

En effet, parfois les TYPES/Classes utilisés sont :
* Orientés par rapport au "rôle joué"» (=> Ce qu’ils "FONT"). Exemples : "Client", "Produit Fourni"   
Ou bien
* Orientés par rapport à leur "nature" (=> Ce qu’il "SONT") : Exemples : "Organisation", "Logiciel"

Et cela pose un problème car un ITEM/Individu donné peut être "en même temps" : 
* un "Client" ET une "Organisation"   
OU   
* un "Client" ET une "Personne"

De la même manière, un ITEM/Individu donné peut être "en même temps" : 
* un "Produit Fourni" ET un "Logiciel"   
OU   
* un "Produit Spécifié" ET un "Logiciel"

Par conséquent, on se trouve "de facto" dans une situation où la modélisation basée sur une approche "Mono-TYPE" touche à ses limites.
Il nous faut un nouveau paradigme de modélisation plus souple, plus expressif, ...
> En bref, qui "colle" mieux à la réalité du terrain !

C’est là qu’intervient la dichotomie "Intention VS Extension".

Qu'est-ce que c'est ?
==
La dichotomie "Intention VS Extension" est une technique de modélisation.    
Elle s'appuie sur le principe de "Separation Of Concerns" appliqué dans le contexte d'une cartographie d'écosystème et se décline sur chacun de ses questionnements clefs : 
* <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/INT_vs_EXT_Who_FR.md">Qui ?</a> (=> <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Agent.md">@Agent</a>)
* <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/INT_vs_EXT_What_FR.md">Quoi ?</a> (=> <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Deliverable.md">@Deliverable</a>)
* <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/INT_vs_EXT_How_FR.md">Comment ?</a> (=> <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Technology.md">@Technology</a>)
* <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/INT_vs_EXT_ForWhat_FR.md">Pour Quoi ?</a> (=> <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Market.md">@Market</a>)
* <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/INT_vs_EXT_Why_FR.md">Pourquoi ?</a> (=> <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Finality.md">@Finality</a>)

En effet, dans ce contexte, les CHOSES identifées dans la cartographie ont 2 ASPECTS différents et complémentaires : 
* L’ASPECT "Intentionnel" d’un ITEM/Individu est relatif à la raison pour laquelle il apparaît dans la carte, au rôle qu’il y joue, à ce qu’il "FAIT" (INDEPENDAMMENT de sa "nature"),
* L’ASPECT "Extensionnel" d’un ITEM/Individu est relatif à sa "nature" profonde, à ce qu’il "EST" (INDEPENDAMMENT du "rôle qu’il joue")

>__S’il n’y avait qu’une seule chose à retenir ça serait que :__   
> Il n’y a PAS d'un côté des ITEMS/Individus intentionnels ET de l'autre des ITEMS/individus extensionnels ...   
> ... MAIS UNIQUEMENT des ITEMS/Individus qui ont un ASPECT intentionnel ET un ASPECT extensionnel.


A quoi ça sert ?
==
Cette technique de modélisation permet de faciliter la __modularisation__ et la __ré-utilisation__ de sous-parties de modèle.

En effet, les modèles intentionnel et extensionnel étant ORTHOGONAUX entre-eux ...    
... ils accueillent chacun uniquement la PROJECTION de l'ASPECT correspondant.

Cela permet de ne gérer dans chaque modèle que caractéristiques et les relations qui lui sont propre.

> D'une certaine manière, cette approche sert à ne pas mélanger des éléments qui ne relève pas de la même logique.

Globalement le modèle intentionnel à un caractère hautement générique qui lui perment d'être pertinent dans le contexte d'une grande variété d'écosystèmes.   
A contrario, les modèles extentionnels sont plutôt spécifiques, ce qui permet à chaque cartographie d'écosystème d'utiliser un modèle qui "colle" bien à la réalité du terrain.

Quels en sont les avantages ?
==
Les principaux avantages de la dichotomie "Intention VS Extension" sont les suivants :
* Permet de ne pas mélanger des notions qui n'ont rien à faire ensemble
* Permet de rationaliser la gestion des propriétés et des relations
* Permet de faciliter la maintenance et l'évolution de modèles complexes
* Permet d'éviter l'explosion combinatoire des classe à gérer (En particulier pour "Deliverable")
* Permet de faciliter le passage de l'informel au formel (En particulier pour "Market" et "Finality")

Comment ça marche ?
==
Techniquement cela est rendu possible par le __typage multiple__ (qui est une mécanique de modélisation de niveau ITEM/Individu)   
Cette approche est plus pertinente que l’héritage multiple (qui une mécanique de modélisation de niveau TYPE/Classe) qui lui ne permet pas d’éviter l’explosion combinatoire des TYPES/Classes)

Cf : https://github.com/iPlumb3r/KeQuarks/blob/master/Features/Multi-Typing_FR.md

Pourquoi l'approche "classique" ne peux pas marcher !
==
Dans une cartographie d’écosystème les CHOSES "SONT" et "FONT" tout à la fois, ...   
... Et seul le principe de "SEPARATION of CONCERNS" nous permet de traiter cette "schizophrénie" dans 2 PLANS complémentaires ORTHOGONAUX entre-eux.

Autrement dit, essayer de tout traiter sur un UNIQUE PLAN mélangerais forcement des notions qui n’ont rien à voir entre-elles.


Ressources
==

Un cas d'usage emblématique : <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/0_UseCases/Bob_develops_SmartphoneCase_FR.md ">Bob develops Smartphone Case</a>    
Un article sur <a href="https://www.linkedin.com/pulse/les-invariants-m%C3%A9tiers-du-plm-bernard-chabot/
">Les Invariants Métiers du PLM</a>
