# API :
+ - What does REST stand for? 
representational state transfer

+ - REST APIs are designed around a resources

+ - What is an identifer of a resource? 

Resource identification refers to the unambiguous reporting of research resources such as genes, organisms, tools, 
and reagents (such as antibodies). These resources should be reported within publications with enough information that reviewers and subsequent researchers can identify the exact strain or reagent used. Preferably, 
authors should provide the full, descriptive name of the resource, its source and a unique identifier

+ - What are the most common HTTP verbs?
 The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read,
  update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently
  
  + - What status code does a successful GET request return?
  returns HTTP status code 200 (OK)
  
   + - What status code does an unsuccessful GET request return? 
   return 404 (Not Found).
   
   + - What status code does a successful POST request return?
   
   it returns HTTP status code 201 (Created). The URI of the new resource is included in the Location header of the response
   
   + - What status code does a successful DELETE request return?
   
   HTTP status code 204 (No Content)
