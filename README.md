# CMPE275
Name:       RAVITEJA KOMMALAPATI
SJSUID:   012526358
emailID:   raviteja.kommalapati@sjsu.edu

Lab 0 - Spring HelloWorld Application

A simple spring basic project to print Hello world on to the console.

### Technologies used

Spring 5.0.8.RELEASE
Maven 3.7.0
java 1.10
Junit 4.12
log4j 1.2.17

Project Dependencies:
  <dependency>
    <groupId>org.springframework</groupId>
    <artifactId>spring-context</artifactId>
    <version>${springcontext.version}</version>
</dependency>
<dependency>
    <groupId>junit</groupId>
    <artifactId>junit</artifactId>
    <version>${junit.version}</version>
    <scope>test</scope>
</dependency>
<dependency>
    <groupId>log4j</groupId>
    <artifactId>log4j</artifactId>
    <version>${logger.version}</version>
</dependency>

Steps I followed
After adding required dependencies to pom.xml and building it successfully I started writing code.
1)Written Greeter interface in interfaces package.
2)Implemented Greeter in the Greet class.
3)Placed required constants in ProjectsConstants.
4)Written application context.xml file and configuration of beans in the file and setting up the parameter values.
5)Written a Junit test case to test the project.
6)Logged the out put to the console using log4j api.

How to run the app
To test the lab0 project I have create a test class using Junit named GreetTest
Just by running it will print the out put required.
"Hello world from Raviteja Kommalapati!"
The values Hello world from  and ! are constant value in project.



