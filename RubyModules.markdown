Ruby modules act super cool. They wrap themselves as an anonymous class and injects themselves into the Ancestor chain.

* Also known as include classes and even sometimes proxy classes.
* When a module is included it bumps to right above the object chain right after the method.
  * If another module is included directly afterward it bumps the first module up the chain and the second is right behind the current method. Lookup {{RubySelf}}
* Most often USED to create a sort of namespace for methods so not to stomp on existing methods along the call stack.