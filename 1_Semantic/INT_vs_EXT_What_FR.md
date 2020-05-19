Questionnement
==
Il s'agit globalement de répondre à la question clef "QUI ?".   
C'est à dire :
* De quoi s'agit-il ? 
* Quelle "chose" est manipulé ?

Concept Intentionel
==
Dans une cartographie d'écosystème, les choses manipulées sont par définition des <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Deliverable.md">@Deliverable</a>.

> C'est ce concept qui incarne ce que "FONT" les ITEMS/Individus de cette catégorie.

Ce sont des "choses" (généralement des produits ou des services) qui définissent par « ce qu’ils font », par la finalité qu’ils incarnent.   
Leur "intentionnalité" se mesure sur une sorte d'échelle par rapport au niveau de maturité entre :
* le stade où "le produit/service n'en est pas encore un", mais c'est juste une "idée" (d'un besoin à fatisfaire ou d'une fonction à remplir)   
ET
* le stade où le produit existe "physiquement" et/ou le service est "en cours d'execution"

Ces différents niveaux correspondent en fait au livrable principal des grandes activités du processus de gestion du cycle vie produit (Définition, Conception, Industrialisation, Production, Distribution, Vente, …)

Ces différents niveaux sont classiquement les suivants :
![Ladder](https://github.com/iPlumb3r/EcosystemMapping/blob/master/images/Intention_Ladder_2020-05_19.png)

__Remarque 1 :__ Utiliser le terme "Livrable" permet d'éviter de dire à chaque fois "Produit ou Service ou Procédé ou Méthode ...")   
__Remarque 2 :__ Les 2 premiers niveau (sur la gauche) ne sont pas - encore - des Produits ni des Services ...     
__Remarque 3 :__ Il est préférable de ne conserver dans l'appellation finale que la partie "statut" (ainsi cela peut s'appliquer à des Produits, mais également à des Services, voire à des Procédés de fabrication ou des Méthodes de travail, ...)   

Voici donc les 6 <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Deliverable.md">@Deliverables</a> clefs, "purement" définis :   

<table>
    <thead>
        <tr>
            <th>ID</th>
            <th>Terme Préféré</th>
            <th>Terme(s) Alternatif(s)</th>
            <th>Description</th>
            <th>Commentaires(s)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>#1</td>
            <td>As Required</td>
             <td>Besoin, Usage, Finalité, ...</td>
            <td>Livrable qui se décrit uniquement par la finalité de son usage indépendament de "ce qu'il fait" pour l'obtenir</td>
            <td>Ce n'est pas vraiment un un "Produit" (ni un "Service"), mais plutôt un ensemble d'exigences à satisfaire. Traditionement documenté par un "Cahier des Charges"</td>
        </tr>
        <tr>
            <td>#2</td>
            <td>As Defined</td>
             <td>Fonctionalité, Besoin fonctionel, Fonctions, ...</td>
            <td>Delivrable qui se décrit uniquement "ce qu'il fait" indépendament de "ce qu'il est"</td>
            <td>Ce n'est pas vraiment un "Produit" (ni un "Service"), mais plutôt un ensemble de fonctions à remplir. Traditionement documenté par un "Cahier des Charges Fonctionel"</td>
        </tr>
        <tr>
            <td>#3</td>
            <td>As Designed</td>
             <td>Livrable technique, Livrable de référence, Livrable spécifié, Livrable générique, ...</td>
            <td>Delivrable qui se décrit uniquement "ce qu'il est" indépendament de "la manière de le faire"</td>
            <td>C'est un "Produit" (ou un "Service") défini par en ensemble de contraintes techniques à cibler. Traditionement documenté par une "Spécification technique"</td>
        </tr>
        <tr>
            <td>#4</td>
            <td>As To Built</td>
             <td>Livrable industriel, Livrable spécifique, Livrable produit/process, Solution globale, ...</td>
            <td>Delivrable qui se décrit par "sa manière de le faire", indépendament de son "lieu de réalisation"</td>
            <td></td>
        </tr>
        <tr>
            <td>#5</td>
            <td>As To Built Local</td>
             <td>Livrable industriel local, Solution Locale, ...</td>
            <td>Delivrable qui se décrit par "son lieu de réalisation"", indépendament de son "temps de réalisation"</td>
            <td></td>
        </tr>
        <tr>
            <td>#6</td>
            <td>As Built</td>
             <td>Livrable réel, Livrable physique, Livrable individual, ...</td>
            <td>Livrable réalisé en une "temps" particulier, dans un "lieu" particulier et selon un "mode de réalisation"  particulier</td>
            <td>Typiquement un produit "physique" ou un Service "en cours d'exécution"</td>
        </tr>
    </tbody>
</table>

__Remarque 4 :__ Il est possible qu'un ITEM/Individu "du monde réel" soit en fait "à cheval" entre 2 de ces "status", mais comme il est impossible de prévoir à l'avance toute les combinaisons possibles, le fait de se baser sur des définions "pures" permet de disposer d'invariants aussi stable que répandus ! Les cas d'ITEM/Individus "à cheval" entre 2 "status" peuvent être résolus via du multi-typing ...

Concepts Extensionnels
==
Le __concept intentionel__ d'<a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Deliverable.md">@Deliverable</a> et ses sous-types incarne des "cible" dont le rôle peut être joué par une série de __concept extensionnels__ que sont les <a href="https://github.com/iPlumb3r/EcosystemMappingModel/blob/master/1_Semantic/Conceptionary/%C2%A7Resource.md">§Resources</a> 

> C'est ce concept et ses sous-types qui incarne ce que "SONT" les ITEMS/Individus de cette catégorie.

En effet, ces derniers se définissent par par leur incarnation dans l'espace-temps, comme par exemple les avions, les voitures, les ordinateurs, les vêtements, les aliments, les logiciels, les services, procédé de fabrication, les méthode de travail, ...   
... bref toutes les catégories (et sous-catégories) de produit que l’on trouvent dans la « nature ».

Le 1er niveau de décomposition des §Resources fait écho à la question "en quoi sont-ils fait ?" :
* Atom-Based Resource
* Bit-Based Resource
* Concept-Based Resource
* Energy-Based Resource

Remarque
==
Il s'avère que pour déterminer de manière non ambiguë « de quel produit on parle exactement», il est nécessaire de spécifier sur quelle « intersection » il se trouve. Par exemple :
* Un logiciel "tel que conçu"
* Une pizza "tel que à fabriquer"
* Un vélo "tel que fabriqué"


Dans la fiche sur le "Typage multiple" : https://github.com/iPlumb3r/KeQuarks/blob/master/Features/Multi-Typing_FR.md
Il y a une représentation qui montre d'où viennent les propriétés d'un produit particulier

Ressources
==
Les différents concepts relatifs à l'ASPECT intentionel des ITEM/Individu répondant à la question "Quoi ?" sont décrit dans l'article <a href="https://www.linkedin.com/pulse/les-invariants-m%C3%A9tiers-du-plm-bernard-chabot/">Les invariants métiers du PLM</a>


Dans la fiche sur le <a href="https://github.com/iPlumb3r/KeQuarks/blob/master/Features/Multi-Typing_FR.md">Typage Multiple</a>, il y a une représentation qui montre d'où viennent les propriétés d'un produit particulier.


