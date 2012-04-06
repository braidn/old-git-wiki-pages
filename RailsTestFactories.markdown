###Factories

* Instead of specifying your data directly, you build a blueprint that will construct your slice of data
* Three really popular gems in order:
  1. Factory Girl
  1. Machinist
  1. FixtureReplacement
* Using dynamic content is allowed by passing a block to the db value
  * Ex: `start_date { Date.today }`
  * In addition, you can reference previous fields in blocks as well

###In Tests

* Assign a var to a `Factory.create(:factoryName, :modifiedAttribute => "Value")`
  * Any valid attribute can be passed into the hash after the factory name
  * Also can be written as `Factory(:factoryName)`
  * Or assign itself to an instance var in a setup block

###Sequencing (Building Unique Things)

* [Sequence Example][0]
* Can be referred to explicitly by calling `Factory.next(:sequenceName)` on any atribute
  * This can be __completely__ negated if the attribute name matches the sequence name



[0]: /RailsTestFactoriesSequenceExample