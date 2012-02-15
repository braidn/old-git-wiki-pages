* `Action View::Helpers::Asset Tag Helper` and `Action View::Helpers::Url Helper` modules contain a number of methods that let you reference resources external to the current template
* `link_to name, options, html_options`
  * ex: `link_to 'Name', new_article_path, :class => 'awesome_sauce'`
  * could also be written as `link_to 'Name', {:controller => 'articles', :action => 'new'}, {:class => 'awesome_sauce'}` 