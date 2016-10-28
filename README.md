#Instructions

This server has created for the http-hello-goodbye-world assignment and was written by Will Nickerson.

##Basic Use
Basic responses are determined by the url path. The responses are as follows:

-http//:localhost:8080/ displays a figlet for "Hello World!"  
-http//:localhost:8080/goodbye displays a figlet for "Goodbye World"
-http//:localhost:8080/"some-bad-path" displays a figlet for "404 PAGE NOT FOUND"

###Posting

Making a post request on the path '/post' causes the server to respond with a figlet that says "Thank you for posting!"

###Querying

To query the servers extensive DB of cats, simply put in the path "/cats/" followed by a querystring with the property "id" set equal to an integer value.
  i.e. http://localhost:8080/cats?id=1

This will display information about that cat. If no cat matches your query and appropriate message will be shown.
