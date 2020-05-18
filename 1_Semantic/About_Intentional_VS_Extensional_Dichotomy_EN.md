Introduction
==
To make the most of the E2M ontology, it is crucial to understand __the ins and outs__ of the "Intention VS Extension" dichotomy : 
* What is it ?
* What is it for ?
* What are the benefits ?
* How does it work ?
* Why can't the "classic" approach work !

Preamble / Background
==
The "Intention VS Extension" dichotomy is a modeling technique that was developed following the observation of the difficulty of making a "common core" emerge between different ecosystem mappings even though it would have been quite logical to be able to make one emerge !
> examples: PAIR, Petit Débrouillards, Alternatiba, DFC, dWeb x SW ...

After analysis, it appears that the reason for this failure is essentially linked to the "monolithic" nature of the models that were developed. Monolithic in the sense that each ITEM/Individual on the map can only belong to 1 and only 1 TYPE/Class and each model has to deal with TYPES/Classes which are not very homogeneous between them because they are based on diametrically opposed logic (BUT totally complementary).

Indeed, sometimes the TYPES/Classes used are :
* Oriented in relation to the "role played"". (=> What they "ARE"). Examples: "Customer", "Product Supplied".
Or...
* Oriented to their "nature" (=> What they "ARE"): Examples: "Organization", "Software"

And this poses a problem because a given ITEM/Individual can be "at the same time" : 
* a "Customer" AND an "Organization" 
OR
* a "Client" AND a "Person"

Similarly, a given ITEM/Individual may be "at the same time" : 
* a "Supplied Product" AND "Software" 
OR
* a "Specified Product" AND a "Software".

Consequently, we find ourselves "de facto" in a situation where modelling based on MONO-TYPE is reaching its limits.
We need a new modeling paradigm that is more flexible, more expressive, ...
> In short, one that "sticks" better to the reality on the ground !

This is where the "Intention VS Extension" dichotomy comes in.

What is it?
==
The dichotomy "Intention VS Extension" is a modeling technique.    
It is based on the principle of "Separation Of Concerns" applied in the context of ecosystem mapping. 

Indeed, in this context the THINGS identified in the mapping have 2 different and complementary ASPECTS: 
* The "Intentional" ASPECT of an ITEM/Individual is relative to the reason why he appears in the map (INDEPENDENT of his "nature"), to the role he plays in it, to what he "DOES".
* The "Extensional" ASPECT of an ITEM/Individual is relative to its deep "nature", to what it "IS" (INDEPENDENT of the role it plays).


__Note__ :  
If there was only one thing to remember, it would be this :   
There are NO intentional ITEMS/individuals AND ITEMS/extensional individuals ...   
... BUT ONLY ITEMS/Individuals who have BOTH an intentional ASPECT AND an extensional ASPECT


What's that for?
==
The intentional and extensional models are ORTHOGONAL models that accommodate the PROJECTIONS of the corresponding ASPECTS. They allow to manage the characteristics and relationships that are specific to each ASPECT.

This approach serves above all to avoid mixing elements that are not part of the same logic.

What are the advantages?
==
The main advantages of the "Intention VS Extention" dichomy are the following:
* Allows to streamline the management of properties and relationships
* Avoids combinatorial explosion of the classes to be managed (Especially for "Deliverable")
* Facilitates the transition from the informal to the formal (Especially for "Market" and "Finality")

How does it work?
==
Technically this is rendered by multiple typing (it is a modeling mechanic at the "ITEM/Individual" level).
This approach is more relevant than multiple inheritance (which a modeling mechanics of level " TYPE/Class " which does not allow it to avoid the combinatorial explosion of TYPES/CLASSes)

Cf: https://github.com/iPlumb3r/KeQuarks/blob/master/Features/Multi-Typing_EN.md

Why can't the "classic" approach work!
==
In an ecosystem cartography the THINGS "ARE" and "ARE" at the same time, ...   
... And only the principle of "SEPARATION of CONCERNS" allows us to treat this "schizophrenia" in 2 complementary ORTHOGONAL PLANS.

In other words, trying to treat everything on a SINGLE PLAN would necessarily mix up notions that have nothing to do with each other.

Resources
==

An emblematic use case: https://github.com/iPlumb3r/EcosystemMapping/blob/master/0_UseCases/Bob_develops_SmartphoneCase_EN.md   
An article about Business Invariants: https://www.linkedin.com/pulse/les-invariants-m%C3%A9tiers-du-plm-bernard-chabot/ (Could be translated with https://www.deepl.com/translator)

