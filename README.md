# layered-architecture-example
build a classic layered backend application.
The application should interact with a relational database (h2) and provide access through http endpoints. It will be executed inside a web container like Tomcat.

The following layers should be implemented (and visible as package):

    persistence - containing the interaction with the database
    model - all model / business logic classes
    service - implementing the use cases of the application
    presentation - all classes required to provide interaction with the application

Don't forget to test your implementation!
