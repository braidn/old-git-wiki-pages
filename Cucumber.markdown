Way to build a scenario in human readable language.

* To install a skeleton in a rails project: `rails g cucumber:install`
  * This also creates several handy rake tasks that can be seen by `rake -T`
* Consist of three parts: Title, Brief Narrative, any amount of Scenarios
* Anything above the `Scenario` declaration is just documentation and considered a `Feature:` block
  * Anything below it are steps in the specific scenario
* Each step begins with 5 possible words: `Given, When, Then, And, But`
* In many instances considered integration tests.
* All matches are returned as a String based variable.