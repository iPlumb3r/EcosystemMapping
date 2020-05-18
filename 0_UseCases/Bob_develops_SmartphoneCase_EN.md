Introduction
==
Use case is not intended to be "totally correct", ...   
... but only to try to bring the principle of "Separation Of Concerns" applied to the dichotomy "Intention VS Extension" into play.

If there was only one thing to remember, it would be this:
* There are NO intentional ITEMS/individuals AND ITEMS/individuals extensionals ...   
* ... BUT ONLY ITEMS/Individuals who have an intentional ASPECT AND an extensional ASPECT

As a result, the INT and EXT models are ORTHOGONAL models which accommodate the PROJECTIONS of the corresponding ASPECTS ...      
... and which allow to manage the relations and characteristics that are specific to each ASPECT.

Scope
==
The dichotomy "Intention VS Extension" being easier to understand for the "Who?" and the "What?", the use case will be limited to the connection of the concepts related to these 2 questionings!

Description
==
The use case is centered on "Bob", a person who develops smartphone cases.   
To do so, he uses the "requirements" defined by the "NormPlus" organization to determine the dimensions he has to meet and "Blender", a CAD software to develop his own case models.   
"Bob" then transmits the "specifications" of each case model to the "FL-Print" organization which will manufacture the case using a "3D Printer" and "Bio-Plastic Filament".

Analysis
==
When we look at the Concepts underlying this use case, we dispute :
* on the one hand that they can be structured according to a particular question they answer, 
* on the other hand that each ITEM/Individual has an intentional ASPECT (in relation to what he "does") AND an extensional ASPECT (in relation to what he "is") with each time a particular Concept to embody this or that ASPECT.

__Example with "Who ?" Concepts__
<table>
    <thead>
        <tr>
            <th>ITEM/Individual</th> 
            <th>Commentaire</th>   
            <th>Intensional TYPE/Class</th>
            <th>Extentional TYPE/Class</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Bob</td>
            <td>Develops smartphone case</td>
            <td>Agent</td>
            <td>Person</td>
        </tr>
        <tr>
            <td>NormPlus</td>
            <td>Specify requirement to respect for smartphone case</td>         
            <td>Agent</td>
            <td>Organization</td>
        </tr>
        <tr>
            <td>FL-Print</td>
            <td>Build smartphone case using 3D printing</td> 
            <td>Agent</td>
            <td>Organization</td>
        </tr>
    </tbody>
</table>

__Example with "What ?" Concepts__
<table>
    <thead>
        <tr>
            <th>ITEM/Individual</th> 
            <th>Commentaire</th>   
            <th>Intensional TYPE/Class</th>
            <th>Extentional TYPE/Class</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Requirement "to be respected" for the iPhone X case</td>
            <td>Define dimentional constraint. Potentially documented by a technical specification</td>
            <td>As Designed</td>
            <td>Product</td>
        </tr>
        <tr>
            <td>Blender</td>
            <td>CAD Software</td>         
            <td>As To Be Built</td>
            <td>Logiciel</td>
        </tr>
        <tr>
            <td>Technical dimention of model A for iPhone X case</td>
            <td>Défini des contraintes dimensionelles. Potentially documented by a technical sheet</td>
            <td>As To Be Built</td>
            <td>Product</td>
        </tr>
        <tr>
            <td>MakerBot</td>
            <td>3D Printer </td>
            <td>As Built</td>
            <td>Product</td>
        </tr>
        <tr>
            <td>Exemplar 1 of model A for iPhone X case</td>
            <td>"Physical" Smartphone case</td>
            <td>As Built</td>
            <td>Product</td>
        </tr>
        <tr>
            <td>BioPlastic Filament</td>
            <td>BioPlastic for smartphone case</td>
            <td>As Built</td>
            <td>Matter</td>
        </tr>
    </tbody>
</table>

__Schema__ :
![alt text](https://github.com/iPlumb3r/EcosystemMapping/blob/master/images/UC_Bob_develops_SmartphoneCase.png)

Note
==
In the case of the "Who?", there is only one intentional Concept that is Agent, but in the case of the "What?" there are several Concepts that correspond to the different levels of abstraction of a Product/Service. 
The most concrete level corresponds to the "physical" product (or the "realized" service), the other levels embody the main stages necessary to be able to realize them.
