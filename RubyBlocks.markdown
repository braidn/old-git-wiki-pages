* Always return a value
* If you have a method you can pass a block to it by encapsulating it with `{ |usableVariable| doStuffHere}`
  * Within the method you can check if a block is given with `block_given?`
  * because this has a question mark it returns either a true or a false value
* Makes good sense to name an iterator block starting with the word `each_`
* calling `include Enumerable` will [embody your class with some powerful collection techniques][0]

[0]: /RubyEnumerable