# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Chapter 2 Exercise 1 
* 1 The browser issues a request for the /users/1/edit URL
* 2 Rails routes /users/1/edit to the index action in the Users Controller (users.controller.rb)
* 3 The index action asks the User model to retrieve User 1 (User.1)
* 4 The User model pulls user 1 from the database
* 5 The User model returns user 1 to the controller
* 6 The controller captures user 1 in the @users variable, which is passed to the index view.
* 7 The view uses embedded Ruby to render the page as HTML.
* 8 The controller passes the HTML back to the browser.

* Chapter 2 Exercise 2: Find the line in the scaffolding code that retrieves the user from the database in the previous exercise.
* <td><%= link_to 'Show', user %></td>

* Chapter 2 Exercise 3: What is the name of the view file for the user edit page?
* edit_user_path(user)

* Chapter 2 further Exercises
* 1 (For readers who know CSS) Create a new micropost, then use your browser’s HTML inspector to determine the CSS id for the text “Micropost was successfully created.” What happens when you refresh your browser?
p id = "notice"
* 2 Try to create a micropost with empty content and no user id.
It actually works - displays "Micropost was successfully created" and then appears in the list of all microposts.
* 3 Try to create a micropost with over 140 characters of content (say, the first paragraph from the Wikipedia article on Ruby).
Works fine and isn't truncated in list of all microposts.
* 4 Destroy the microposts from the previous exercises.
Done.

* Ch2 even more exercises
* q1: doesn't let me add the same long content. Displays error message and the content is not added as a micropost.
* CSS id: div id = "error_explanation"

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
