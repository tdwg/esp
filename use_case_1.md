#Use Case 1 Single fossil mandible fragment, DIK-24-1#
##Abstract##
This use case documents the example of a single mammalian fossil mandiblular fragment (left mandible fragment with m1 crown) from the Dikika study area in NE Ethiopia. Details about the specimen are available in Geraads et al. 2011. Enhydriodon Dikikae sp. nov (Carnivora: Mammalia), A gigantic otter from the Pliocene of Dikika, Lower Awash, Ethiopia. Journal of Vertebrate Paleontology. 31(2):447-453.
##Comments##
The speciment is assigned to a new species but is not the holotype. This should be a fairly common fossil use case.
##Darwin Core Encoding##
###Record-level Terms###
```dcterms:type: 'Physical Object'```   
or "http://purl.org/dc/dcmitype/PhysicalObject" See [issue #3](https://github.com/tdwg/paleo/issues/3)   
    
```dcterms:modified: "2017-03-07T18:37-0600"```    
String literal representing 7 March 2017 at 6:37 PM Central Time. Should ISO 8601 be best practice? See [Issue #5](https://github.com/tdwg/paleo/issues/5).   
    
```dcterms:language: "en"```  
Recommended Darwin Core best practice is controlled vocabulary such as RFC 4646.   
   
```dcterms:license: ```   
What is recommended best practice for licensing in academic and/or commercial paleontology? See [issue #6](https://github.com/tdwg/paleo/issues/6)  
   
```dcterms:rightsHolder:'Authority for Research and Conservation of Cultural Heritage, Ethiopia' ```  
[ARCCH](http://www.mysc.gov.et/ARCCH.html). Need a controlled vocabulary for institutions and rights holders in paleobiology.See [issue #7](https://github.com/tdwg/paleo/issues/7).  
    
```dcterms:accessRights: ```   
Need documentation on how accessRights differs from dcterms:license, and some guidelines on best practices. See [issue #8](https://github.com/tdwg/paleo/issues/8).  
    
```bibliographicCitation:'Geraads D, Alemseged Z, Bobe R, et al. 2011. Enhydriodon dikikae, sp. nov. (Carnivora: Mammalia), a gigantic otter from the Pliocene of Dikika, Lower Awash, Ethiopia. J Vert Paleontol 31:447–453.' ```   
What citation format is recommended? see [issue #9](https://github.com/tdwg/paleo/issues/9).  
   
```dcterms:references:http://paleocore.org/projects/drp/810 ```   
URI to the data record for the fossil specimen. How do we include multiple references? What is best practice for generating specimen URIs and how are they related to globally unique IDs? See [issue #10](https://github.com/tdwg/paleo/issues/10).   

```institutionID: ```     
Darwin Core best practice is to point to a collection registery. What if collection and institution not registered?  How does this relate to [issue #8](https://github.com/tdwg/paleo/issues/8) for rights holder?    
   
```collecitonID: ```   
See above and [issue #8](https://github.com/tdwg/paleo/issues/8)   
    
```datasetID: ``` 
See above and [issue #8](https://github.com/tdwg/paleo/issues/8)   
   
```institutionCode:'NME' ```   
National Museums of Ethiopia. See [issue #8](https://github.com/tdwg/paleo/issues/8)   
   
```collectionCode:'DIK' ```   
Collection area within permit area.   

```datasetName: 'DRP' ```   
Project acronym.   
   
```ownerInstitutionCode: 'ARCCH' ```
'Authority for Research and Conservation of Cultural Heritage, Ethiopia'. How does this differ from dcterms:rightsHolder? [Issue #11](https://github.com/tdwg/paleo/issues/11).   
   
```basisOfRecord:'FossilSpecimen' ```   
basisOfRecord refines dcterms:type, by providing a second type descriptor. Recommended best practice is to use a Darwin Core Class. As with dcterms:type there is the question of whether a string literal or URI is best. [Issue #3](https://github.com/tdwg/paleo/issues/3).   
   
```informationWithheld: ```   
What is best practice for indicating None?  [Issue #12](https://github.com/tdwg/paleo/issues/12).     
   
```dataGeneralizations: ```
See above.    
   
```dynamicProperties: ```
Best practice is to include a JSON or other encoded file.   
   

###Occurrence###
```occurrenceID: "ENM-DIK-24-1"```   
Need a recommended best practice for assigning truly global unique IDs to fossils. [Issue #13](https://github.com/tdwg/paleo/issues/13)
   
   
