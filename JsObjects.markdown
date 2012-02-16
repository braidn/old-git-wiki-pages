* How to create: JsCreatingObjects  
* JsObjectProperties

###Type Checking

* `typeof object` will return what type of object is being referenced
* `object.has_Own_Property("property")` will return a true or false if the property exists in the object

###Looping

printing out all variables:

     for(var property in nyc) {
       console.log(property);
     }
    for(var property in nyc) {
      var myProperty = nyc[property];
      console.log(myProperty);
    }