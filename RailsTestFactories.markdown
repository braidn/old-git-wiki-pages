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

* Assign a var to a `Factory.create(:factoryName, :modifiedValue => "Value")`
  * Any valid value can be passed into the hash after the factory name
  * Also can be written as `Factory(:factoryName)`
  * Or assign itself to an instance var in a setup block

###Sequencing (Building Unique Things)

* [Sequence Example][0]




[0]: /RailsTestFactoriesSequenceExample