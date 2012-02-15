* Apps can have as many as needed
* Get placed in app/sweepers file
  * Class inheritance == Controller Name Sweeper < Action Controller::Caching::Sweeper
  * Require an `observe X` block where X == the name of controller
* Basically a collection of methods for removing caches
* Called in controller with `cache_sweeper :controller_name`