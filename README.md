# socialnetwork
 basic social networking application in Python using a database to store user information and the Flask web framework to handle routing and rendering templates:
 To allow users to post messages in the social networking application, you can add a route that displays a form for creating a new post and handle the form submission to create and save the new post.
 The new_post route renders a template containing a form with a textarea input for the post content and a submit button. When the form is submitted, the new_post_post route is called and creates a new Post object with the content and user ID from the form submission. The new post is then added to the database and the user is redirected back to the homepage.

You will need to make sure that only logged-in users can access the /new_post route by adding a login check in the route function or using a decorator.
