# sbsvc2
REST Webservice using springboot and gradle
This is a sample REST webservice completely self contained using spring boot and gradle. It has everything needed to build and run it in a Tomcat container.

## Setup workspace
1. Clone this repo
	```
	$ git clone https://github.com/gitbaron/sbsvc2.git
	```
2. Build using gradle
	From the command line in the current project path execute the following command. This runs the build using gradle wrapper.
	```
	$ ./gradlew build
	```
3. Run the code
	From command line run the bootRun task using gradle wrapper.
	```
	$ ./gradlew bootRun
	```
	Logging output is displayed. The service should be up and running within a few seconds.

4. Test the Persons service
	There is a persons service that returns an array of pre-coded person names and their ids. Visit ```http://localhost:8080/persons``` to get all the persons.
	Then use the array position (starting with 0) to get the particular person using ```http://localhost:8080/persons/{id}```. Notice that using id value 4 will return an error.

ENJOY !! :thumbsup:

Created for demo1
