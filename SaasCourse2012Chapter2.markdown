###Notes

* The web is a client server architecture
  * client asks the question and the server answers the question
* The server responds with a status code first, headers and a body
* HTTP is [stateless][1]
* Cookies are basically junk placed in the header of the response
  * they solve the problem of keeping track of users from points in the website
* Web server side works with connection to users
* App server side is where all code is run.
* Sharding is where data is portioned out over several different servers
* Replication is direct copies of data over multiple servers

###HTML and CSS

* Descendant from SGML built by IBM
* CSS is the separation from the content and structure
  * Eases issues with screen readers and accessibility
* Best practice: All HTML should have no styling

###Content Generation

* Olden days were templates written mostly in flat HTML files
* Frameworks solved problems when a lot of content generation was needed

###Model-View-Controller

* Simple design pattern
* Separate business logic from presentation, tied together with a controller
* Controllers allow users to talk and inform the user about other controllers/models
* Alternative architectures: 
  * Page Controller (Sinatra)
  * Front Controller (J2EE)
  * Template View (PHP) 

###Models(Databases)

* In Rails it is controlled via ActiveRecord
* Marshaling: basically freezing an object in memory
  * Unmarshaling would be the opposite, bring it out, give it a new object reference, use/modify it.
* Basic operations on an object is CRUD
* Each _row_ in the table == one model instance
* Each _column_ stores a value pertaining to each attribute of the specific model



{::comment}Links{:/}

[1]: http://www.yafla.com/dennisforbes/-Web-Apps-Suck-Because-HTTP-is-Stateless-/-Web-Apps-Suck-Because-HTTP-is-Stateless-.html
