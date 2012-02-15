How to create: JsCreatingObjects

##Type Checking

* `typeof object` will return what type of object is being referenced
* `object.hasOwnProperty("property")` will return a true or false if the property exists in the object

##Looping

printing out all variables:

     for(var property in nyc) {
       console.log(property);
     }