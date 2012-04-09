* where stubs are generated methods, mocks also know which methods should be called and what canned response should be returned.
* all of this is very meta but quite handy.
* 4 different libraries
  1. FlexMock: oldest and less commonly used
  1. Mocha: Used by Rails Core team
  1. Double Ruby: New kid on the block ( Mon, 09 Apr 2012 13:56:27 )
  1. Rspec: Built in mocking library
* Easily used in Rails by adding require 'mocha' to your test_helper.rb file. 

###Stubs

* A replacement for all or sometimes a part of a Ruby object.
* Hashed arguments correspond to the methods that the stubbed object returns