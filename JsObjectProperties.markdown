* All properties assigned to an object are automatically public.
* If a property within ab object is defined without a `this` and with a standard `var` then it is considered _Private_

     
    function Bankaccount (name) {
      this.name = name;
      var bankCredit = 4000;
     }