Three common filters:  
`before_filter, after_filter` and `around_filter`

* The basics is you can pass a method to be run before certain portions of your controller (new, create, destroy, etc)
* Also `skip_before_filter` to skip a particular method that is being applied at the application layer
* The `around_filter` creates a dual filter of sorts. Invoking a before, letting it run, and invoking an after filter.
  * Requires the use of the `yield`
  * If one causes a false value or there is no `yield` then the filter fails.
  * __BENEFIT__: they retain context throughout the entire action.