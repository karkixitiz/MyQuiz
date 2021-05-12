# MyQuiz

### ASP.NET Core Identity
 ASP.NET Core Identity is a fully featured membership system for creating and maintaining user logins. Using Identity API, you can sign in & sign out users, reset their passwords , lockout users & Implement Multi Factor Authentication. It can also integrate with the external login providers like Microsoft Account, Facebook, Google, etc.
When we create a new application, we can install the ASP.NET Core identity by choosing the Individual Accounts under the Authentication Type Option. Most of the Identity related services and UI forms like Register, Login & Logout are automatically created for us.
In this tutorial, we will create the project with No Authentication and then we will add the Identity API. In this way you will learn the Identity API better.
The Identity API uses cookie Authentication. We have also have a tutorial about User Registration & login Using Cookie Authentication. That tutorial does not use the identity API. The Identity API uses the techniques mentioned in the tutorial. Hence we advices you to go through it first.
The Two important Identity services are User Manager and Sign In Manager.

 
 
### User Manager  
The UserManager is a concrete class that manages the user. This Class Creates, Updates, and Deletes the Users. It has methods to find a user by User ID, User Name, and email. UserManager also provides the functionality for adding Claims, removing Claims, add and removing roles, etc. It also generates password hash, Validates Users etc.

### Sign In Manager  
SignInManager is a concrete class which handles the user sign in from the application.
The SignInManager is responsible for Authenticating a user, i .e  signing in and signing out a user. It issues the authentication cookie to the user. 
