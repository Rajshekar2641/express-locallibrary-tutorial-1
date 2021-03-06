# express-locallibrary-tutorial
## About Model View Controller:
- MVC is an application design model comprised of three interconnected parts. They include the model (data), the view (user interface), and the controller (processes that handle input). The MVC model or "pattern" is commonly used for developing modern user interfaces.
-Components:  
1. Model: It includes all the data and its related logic
2. View: Present data to the user or handles user interaction
3. Controller: An interface between Model and View components
he MVC pattern, in a nutshell, is this:

The model represents the data, and does nothing else. The model does NOT depend on the controller or the view.

The view displays the model data, and sends user actions (e.g. button clicks) to the controller. The view can:

be independent of both the model and the controller; or

actually be the controller, and therefore depend on the model.

The controller provides model data to the view, and interprets user actions such as button clicks. The controller depends on the view and the model. In some cases, the controller and the view are the same object.

## About Express-local Library:

1. https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website

1. https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website

1. Reference Repository : https://github.com/mdn/express-locallibrary-tutorial

## Nodemon:
- Enable server restart on file changes using Nodemon
- https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website