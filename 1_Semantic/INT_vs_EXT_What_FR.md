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

Ce sont des "choses" (généralement des produits ou des services) qui définissent par « ce qu’ils font », par la finalité qu’ils incarne. 
Leur "intentionnalité" se mesure sur une sorte d'échelle par rapport au niveau de maturité entre :
* le stade où "le produit n'en est pas encore un", mais c'est juste une "idée" (d'un besoin à fatisfaire ou d'une fonction à remplir)   
ET
* le stade où le produit existe "physiquement" et/ou le service est "en cours d'execution"

Ces différents niveaux sont classiquement les suivants :
![Ladder](https://github.com/iPlumb3r/EcosystemMapping/blob/master/images/Intention_Ladder.png)

__Remarque 1 :__ Les 2 premiers niveau (sur la gauche) ne sont pas - encore - des Produits   
__Remarque 2 :__ Il est préférable de ne conserver dans l'appellation que la partie "statut" (ainsi cela peut s'appliquer à des Produit, mais également à des Services, voire à des Procédés de fabrication ou des Méthodes de travail, ...)
__Remarque 3 :__ Il est possible qu'un ITEM/Individu soit en fait "à cheval" entre 2 de ces "status"

Voici donc les 6 <a href="https://github.com/iPlumb3r/EcosystemMapping/blob/master/1_Semantic/Conceptionary/%40Deliverable.md">@Deliverable</a> clef, "purement" défini : 

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
            <td>#5</td>
            <td>As Built</td>
             <td>Livrable réel, Livrable physique, Livrable individual, ...</td>
            <td>Livrable réalisé en une "temps" particulier, dans un "lieu" particulier et selon un "mode de réalisation"  particulier</td>
            <td>Typiquement un produit "physique" ou un Service "en cours d'exécution"</td>
        </tr>
    </tbody>
</table>

__Remarque 3 :__ Il est possible qu'un ITEM/Individu soit en fait "à cheval" entre 2 de ces "status", mais comme il est impossible de prévoir à l'avance toute les combinaisons possibles, le fait de se baser sur des définions "pures" permet de disposer d'invariant tant stable que répandus !

comme par exemple le produit « tel que requis », le produit « tel que conçu », le produit « tel qu’à fabriquer », le produit « tel qu’à vendre », … bref tous les types de produit qui correspondent au livrable principal des grandes activités du processus de gestion du cycle vie produit (Définition, Conception, Industrialisation, Production, Distribution, Vente, …).

Remarque : L'avantage de la terminologie retenu par E2M ("As Defined", As Designed", "As To Be Built", "As Built") est quelle n'a pas besoin de dire de quoi il agit (et que donc cela peut s'appliquer à une vaste diversité de "choses" (Produit, Procédé, Méthodologie, Service, ...)

Concepts Extensionnels
==

Et c'est justement le rôle des §Resource pendant extensionnel des @Deliverable intentionnels de le faire ...

En effet, ces derniers se définissent par « ce qu’ils sont », par leur incarnation dans l'espace-temps, comme par exemple les avions, les voitures, les ordinateurs, les vêtements, les livres, les aliments, les logiciels, les services … 
... bref toutes les catégories (et sous-catégories) de produit que l’on trouvent dans la « nature ».

Et bien il s'avère que pour déterminer de manière non ambiguë « de quel produit on parle exactement», il est nécessaire de spécifier sur quelle « intersection » il se trouve. Par exemple :
* Un logiciel "tel que conçu"
* Une pizza "tel que à fabriquer"
* Un vélo "tel que fabriqué"

Conséquence
==
Il n'y a donc PAS d'un côté des ITEMS/Individus qui soient des @deliverable (ou des sous-TYPES de @deliverable) et de l'autre des ITEMS/Individus qui soient des §Resource (ou des sous-TYPES de §Resource)
... mais bien des ITEMS/Individus qui sont SIMULTANEMENT des @deliverable (ou des sous-TYPES de @deliverable) ET des §Resource (ou des sous-TYPES de §Resource)

Avantages
==
De cette manière, chaque produit « intersection » est donc caractérisé à la fois par :
 * les caractéristiques (dimension, taille, forme, texture, …) du produit "extensionnel" auquel il appartient,
* mais également par les caractéristiques (code, label, prix, délais de livraison, …) son produit "intentionnel" de référence.

Dans la fiche sur le "Typage multiple" : https://github.com/iPlumb3r/KeQuarks/blob/master/Features/Multi-Typing_FR.md
Il y a une représentation qui montre d'où viennent les propriétés d'un produit particulier

Ressources
==
Les différents concepts relatifs à l'ASPECT intentionel des ITEM/Individu répondant à la question "Quoi ?" sont décrit dans l'article <a href="https://www.linkedin.com/pulse/les-invariants-m%C3%A9tiers-du-plm-bernard-chabot/">Les invariants métiers du PLM</a>
