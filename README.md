# Mancala MVC Java

Maven
-----

Use Maven to compile/build/run your project

==> [Maven Home](https://maven.apache.org/)


### Run the MancalaAPI project

The HTTP port used in this project is defined within the projects POM, so if port 4000 is already in use you can change the portnumber here. From within the MancalaAPI project run the following commands:

    C\>mvn clean package
    C\>mvn jetty:run

Now that the MancalaAPI project is running you can use Postman to test it or go to:

    http://localhost:4000/mancala
	(Change the portnumber if you've changed the port in the projects POM)
