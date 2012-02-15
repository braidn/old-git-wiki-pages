##Classes =>  
Create an Animal class and then assign a Penguin as a Animal

    function Animal(name, numLegs) {
        this.name = name;
        this.numLegs = numLegs;
    }
    Animal.prototype.sayName = function() {
        console.log("Hi my name is "+this.name);
    };

    function Penguin(name) {
        this.name = name;
        this.numLegs = 2;
    };
    Penguin.prototype = new Animal();

Now penguins can do everything that normal animals can do...and maybe more.