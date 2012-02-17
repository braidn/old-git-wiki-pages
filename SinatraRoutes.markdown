Sinatra's main DSL is built off from simple _verb 'route' do_ blocks

* All of the blocks are read from a top-down hierarchy. This becomes important when using wildcard selectors
* Multiple urls with same behavior can be expressed as:

    ['/one', '/two', '/three'].each do |route|
      get route do
        "Triggered #{route} via GET"
       end
      post route do
        "Triggered #{route} via "POST"
       #And so on
      end
     end

*{{SinatraRouteParams}}