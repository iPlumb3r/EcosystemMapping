Introduction
==
Cas d'usage n’a pas vocation à être « totalement juste », ...   
... mais uniquement à essayer de faire toucher du doigt le principe de "Separation Of Concerns" appliqué à la dichotomie "Intention VS Extension"

S’il n’y avait qu’une seule chose à retenir ça serait que :
* Il n’y a PAS des ITEMS/Individus intentionnels ET des ITEMS/individus extensionnels ...   
* ... MAIS UNIQUEMENT des ITEMS/Individus qui ont un ASPECT intentionnel ET un ASPECT extensionnel

De ce fait, les modèles INT et EXT sont des modèles ORTHOGONAUX qui accueille les PROJECTIONS des ASPECTS correspondants ...      
... et qui permettent de gérer les relations et les caractéristiques qui sont propre à chaque ASPECT.

Périmètre
==
La dichotomie "Intention VS Extension" étant plus facile à comprendre pour le "Who ?" et le "What ?", le cas d'usage se limitera à la mise en connection des concepts relatifs à ces 2 questionnements !

Description
==
Le cas d'usage est centré sur "Bob", une personne qui developpe des coques de smartphone.   
Pour ce faire, il se sert des "exigences" définies par l'organisation "NormPlus" pour déterminer les côtes dimentionelles qu'il doit respecter et du logiciel "Blender" pour réaliser le développement de ces propres modèles de coques.   
"Bob" transmet ensuite les "specifications" de chaque modèle de coque à l'organisation "FL-Print" qui va fabriquer les coques en utilisant une "Imprimante 3D" et du "Filament Bio-Platique".

Analyse
==
Lorsqu'on s'intéresse aux Concepts sous-jacents à ce cas d'usage, on contaste :
* d'une part qu'ils peuvent être structurés en fonction d'un questionemment particulier auquel ils répondent, 
* d'autre part que chaque ITEM/Individu dispose d'un ASPECT intentionnel (par rapport à ce qu'il "fait") ET d'un ASPECT extensionnel (par rapport à ce qu'il "est") avec chaque fois un Concept particulier pour incarner tel ou tel ASPECT.

__Exemple avec les Concepts répondant au questionnement "Who ?"__
<table>
    <thead>
        <tr>
            <th>ITEM/Individu</th>
            <th>Commentaire</th>            
            <th>TYPE Intentionnel</th>
            <th>TYPE Extensionnel</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Bob</td>
            <td>Developpe des coques de smartphone</td>
            <td>Agent</td>
            <td>Person</td>
        </tr>
        <tr>
            <td>NormPlus</td>
            <td>Specifie des exigences à respecter pour les coques de smartphone</td>         
            <td>Agent</td>
            <td>Organization</td>
        </tr>
        <tr>
            <td>FL-Print</td>
            <td>Fabrique des coques de smartphone en impression 3D</td> 
            <td>Agent</td>
            <td>Organization</td>
        </tr>
    </tbody>
</table>

__Exemple avec les Concepts répondant au questionnement "What ?"__
<table>
    <thead>
        <tr>
            <th>ITEM/Individu</th>
            <th>Commentaire</th>            
            <th>TYPE Intentionnel</th>
            <th>TYPE Extensionnel</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Exigences "à respecter" pour la coque de l'iPhone X</td>
            <td>Défini des contraintes dimensionelles. Potentielelement documenté dans un "Cahier des Charges"</td>
            <td>As Designed</td>
            <td>Coque de smartphone</td>
        </tr>
        <tr>
            <td>Blender</td>
            <td>Logiciel de conception</td>         
            <td>As To Be Build</td>
            <td>Logiciel</td>
        </tr>
        <tr>
            <td>FL-Print</td>
            <td>Fabrique des coques de smartphone en impression 3D</td> 
            <td>Agent</td>
            <td>Organization</td>
        </tr>
    </tbody>
</table>

Avantages
==

Conclusion
==