# Mancala MVC Java

Maven
-----

Use Maven to compile/build/run your project

==> [Maven Home](https://maven.apache.org/)


### Run the MancalaAPI project

Go to the directory where you'll find the MancalaDomainForwardInitializationComplete JAR and run the following command to install this JAR:

    C\>mvn org.apache.maven.plugins:maven-install-plugin:3.0.0-M1:install-file -Dfile=MancalaDomain-1.0.0-SNAPSHOT.jar
    (this is for version *3.0.0-M1* of the *maven-install-plugin*)

The HTTP port used in this project is defined within the projects POM, so if port 80 is already in use you can change the portnumber here. From within the MancalaAPI project run the following commands:

    C\>mvn clean package
    C\>mvn jetty:run

Now that the MancalaAPI project is running you can use Postman to test it or go to:

    http://localhost/mancala
	(add a portnumber to *localhost* if you've changed the port in the projects POM)
