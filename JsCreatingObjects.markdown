function Person(name, age) {
      this.age = age;
      this.name = name;
    }
    var bob = new Person('bob', 20);

Retrieving object properties

    console.log("Bob's age is " + bob.age);