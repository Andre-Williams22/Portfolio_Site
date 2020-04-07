# Portfolio_Site



- (5 Points) How is this project structure different than a Flask (or Node) application? What role are the urls.py and views.py files responsible for?
The way we connect routes and models to a database is different. For example, how we have to create different apps within the project folder. They are responsible for viewing and connecting information from different apps together.


- (5 Points) Why do we use 2 separate urls.py files? How do they interact?
To organize and separate our apps and routes connect to different pages. When the main page is loaded and there is a message recieved from the client, it will render the url with the correct response.

- (5 Points) When is it desirable to split our code over multiple apps? Why would we want to do so?
This is desired when we have a large scale project that performs many different functions. This method helps us organize our code. 