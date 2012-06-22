###Notes

* Debugging is twice as hard as writing the code in the first place
* Manual testing is when you write something, and then you look at the output
* You the programmer are inherently weighted with testing your code
* Cucumber describes behavior of the app
* Rspec test individual modules that contribute those behaviors in Cucumber
* When adding a new feature == new route+new controller method+ new view(unless we can use a previous view.

###Unit Tests

* Fast, Independent, Repeatable, Self Checking, and Timely.
* The self checking aspect basically deems John White's job useless. Wonder how long that will actually take?
* Rspec is a great tool for building and running unit tests. Due to its complexity it is basically a DSL.
* Spec dir is setup just like an app dir.
* Most of the time we will be writing code for our models and controllers.

###TDD Life Cycle

* Think about one thing the code should do.
* Capture the thought into a test which will fail.
* Write the simplest possible code that lets the tests pass.
* Go back and DRY stuff up.
* __Seams__: A place where you can change your apps behavior without editing the code - Michael Feathers.
* Seams work awesome in testing to isolate behavior of some code from that code it depends on.
* Rspec resets all mocks and stubs after each run.
* Each `it` clause should only do one thing.