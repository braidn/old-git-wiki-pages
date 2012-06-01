* Used to dry up steps
* Responsible for converting a specific capture string into something a bit more meaningful

Syntax:

~~~~
Transform /^\d+$/ do |numb|  
  number.to_i  
end
~~~