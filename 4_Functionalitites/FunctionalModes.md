Functinal Modes
==

All required functions for the EBR (Cf next sections) are defined in order to be compliant with one or the other (or both) of the following functional modes : 
* Model-Driven Mode
* Model-Discovery Mode (=> Reconciliation Mode)

Model-Driven Mode
-
It's a "top-down" mode, where the knowledge base management functionalities :    
* requires a pre-defined #Model in order to create/instanciate any #Individual   

This mode is appropriate when the knowledge domain is well-know and could be easily formalized   
=> This is the case for the __intentional aspect__ of the #Model (= #IntentionalModel)   

In this mode, the #KnowledgeBase is always coherent with the #Model

Model-Discovery Mode
-
It's a "bottom-up" mode, where the knowledge base management functionalities :   
* do NOT requires a pre-defined #Model in order to create/instanciate an #Individual.
* allows create an #Individual with no type (or typed "Thing")
* allows to change the type of an #Individual
* allows to multi-type an #Individual
* allows to defines "on-the-fly" new #Property & # Relation for a #Class

This mode is appropriate when the knowledge domain is NOT well defined ...   
... and/or when the Ecosystem Mapping scope should be extended to an unknow new domain   
=> This is the case for the __extensional aspect__ of the #Model (= #ExtensionalModel)

In this mode, it could appears __incoherencies__ between the #KnowledgeBase and the #Model, BUT this is NOT critical, ...   
... IF those incoherencies should be easily detected, both : 
* At the #KnowledgeBase level, when some #Individual are characterised by #Property and/or #Relation not allowed at the #Model level
* At the #Model level, when new #Property and/or #Relation are used by some #Individuals   

Reconciliation Mode
-
=> This mode permit the User to solve __incoherencies__ : 
* either by deleting "wrong" information at the #KnowledgeBase level, 
* either by accepting new "rigth" constraints at the #Model level.
