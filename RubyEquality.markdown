4 methods that take the cake:

1. `.eql?`
1. `.equal?`
  * tests for object identity
  * `x.equal?(y)`
  * read x object is equal to y object?
1. `==`
1. `===`

### Other Methods

* The `.instance_of?` method will return true if is an instance of the direct class (no inheritance allowed)
  * The `.kind_of?` method will allow inheritance chain lookups
* The `respond_to?` method will see if a class response to a specific class within the method