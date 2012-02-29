Way to build a scenario in human readable language. Best served with large [Capybara Dsl][1] like rodents

* To install a skeleton in a rails project: `rails g cucumber:install`
  * This also creates several handy rake tasks that can be seen by `rake -T`
* Consist of three parts: Title, Brief Narrative, any amount of Scenarios
* Anything above the `Scenario` declaration is just documentation and considered a `Feature:` block
  * Anything below it are steps in the specific scenario
* Each step begins with 5 possible words: `Given, When, Then, And, But`
* In many instances considered integration tests.
* All matches are returned as a String based variable.

###Objects

* Best to use Factory_girl
  * make sure the files from the factories dir (or wherever) is being loaded into the factories.rb file in the support section of Cucumber
    * an [example][2]
* This works because all files in features/support get loaded prior to cucumber running its tests

[1]: /CapybaraDsl
[2]: /FactoryGirlCucumberEnvironment