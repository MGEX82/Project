Coverage: 34%
**STORE SIMULATION

This project is a simulation of a store environment where users can input details of customers, items, orders and order items. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
The development of this project was done using MySQL Workbench 8.0 and Eclipse IDE for Java Developers 22-03. You will also require Maven to help install the program.

To download MySQL Workbench 8.0 please go here: https://dev.mysql.com/downloads/workbench/

To download Eclipse go here: https://www.eclipse.org/downloads/packages/release/neon/2/eclipse-ide-java-developers

To download Maven go here: https://maven.apache.org/download.cgi




### Installing

Maven installation instructions: https://maven.apache.org/install.html

MySQL Workbench installation instructions: https://www.simplilearn.com/tutorials/mysql-tutorial/mysql-workbench-installation

Maven installation instructions: https://maven.apache.org/install.html




## Running the tests

The tests in this package can be split into the following categories@

### Unit Tests 

These tests are given their own classes which are called Test classes. They are effectively simulations of the application classes which give a reliable indicator as to how well the application clases will work using pre-programmed "expected" data

```
There are eight Test classes in this project, two each each connected SQL table.  
```

### Integration Tests 
Integration testing is more generic rather than focussed on a specific class. They test how well classes interact with each other. 

```
Any test in this project that relies on the connection to the SQL database or has to import data from another class is an integration test. Most classes in this project have some degree of this. 
```

### And coding style tests

Coding style testing is a lot more price, it check specific lines of code for bugs and errors. 

```
Commenting out the bulk of the code in a class allows you to test specific lines of code to narrow down where exactly a bug might be.  
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management

## Versioning

We use [SemVer](http://semver.org/) for versioning.

## Authors

* **Chris Perrins** - *Initial work* - [christophperrins](https://github.com/christophperrins)

## License

This project is licensed under the MIT license - see the [LICENSE.md](LICENSE.md) file for details 

*For help in [Choosing a license](https://choosealicense.com/)*

## Acknowledgments

Thanks to Pawel Stypulkowski and other members of my cohort for the help they have given me. 
