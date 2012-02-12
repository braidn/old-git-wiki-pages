Instructions on how your app will handle certain requests(called methods or 'actions'). Some things to think about:  

* Unless otherwise declared, all methods in a controller class are public.
* Usually when actions complete their work they respond by rendering a view by using a RespondToBlock
  * The controller responds to the user exactly once per request.
    This means that you could not have two `render()` methods per request