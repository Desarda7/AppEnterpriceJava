# Maven Hello World Project

Maven Project Lab2

This maven project demonstrates printing "Hello, World!" to the console.

## Prerequisites

Before running this project, ensure you have the following installed:

- Java Development Kit (JDK) 8 or higher
- Apache Maven

## Getting Started

1. Clone this repository to your local machine:

   git clone https://github.com/Desarda7/AppEnterpriceJava.git

After creating a directory on my local pc, i run the command
"mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false"
on command line.

I change the directory by executing "cd my-app" and then i build the project with the command "mvn package"

Build the project using Maven:

mvn clean install

## Then

You should see the following output in the console:
Hello, World!
