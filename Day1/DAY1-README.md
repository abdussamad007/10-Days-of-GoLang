# 10 Days of GOLang

For the next 10 days, learn the GO Programming language.

## Getting Started

[Go Cheat Sheet](./CheatSheet.md)

Cheat Sheets are handy. Lets have a glance how the Go langulage is looks like, basic building blocks and langulage fundamentals.

### Prerequisites

Fresh Mind! It will help you to learn a new langualge in 10 days which will be your 1st basecamp to learn programming Smart Contract in Blockchain.

However, knowing other programing langualge will help you learn faster.


### Day 1: Installing and IDE setup

Install Go on Ubuntu 18.04 is by using the apt command to install Go binaries from the Ubuntu's repository: 

$ sudo apt install golang

This will install the latest traditional package which at the the time of writing is go version go1.10: 

$ go version

go version go1.10 linux/amd64

Before we perform a test we first need to set GOPATH: 

$ echo 'export GOPATH=$HOME/go' >> ~/.bashrc 

$ echo 'export PATH=${PATH}:${GOPATH}/bin' >> ~/.bashrc 

$ source ~/.bashrc 

Perform a go command test with pre-compiled hello world: 

$ go get github.com/golang/example/hello

$ hello 

Hello, Go examples

=========NOW INSTALLATION IS COMPLETED========

Now download and setup Eclipse IDE

1. downlaod java 

Switch to the root user.

$sudo su -

Update the system repository index.

$apt update

Install the wget package to download the Eclipse IDE from the internet over a terminal.

$apt install wget

Eclipse requires Java JDK to be available on your machine. You can either install Oracle JDK or OpenJDK.

$apt install -y openjdk-8-jdk

Verify the Java version on your machine.

$java -version

Output:

openjdk version "1.8.0_162"

OpenJDK Runtime Environment (build 1.8.0_162-8u162-b12-1-b12)

OpenJDK 64-Bit Server VM (build 25.162-b12, mixed mode)

Install Eclipse.

We will be installing Eclipse using the snappy packaging system. To download and install the Eclipse snap package on your system, 
type:

$sudo snap install --classic eclipse

On successful installation of Eclipse, you should see the following output:

eclipse 4.8.0 from 'snapcrafters' installed

Starting Eclipse

Now that Eclipse is installed on your Ubuntu system you can start it by clicking on the Eclipse icon (Activities -> Eclipse):

When you start Eclipse for the first time, a window like the following will appear asking you to select a Workspace directory:

The default directory should be fine. Click Launch to proceed:

=====================NOW INSTALL GO PLUGIN IN ECLIPSE=====

Please follow the instruction mentioned https://marketplace.eclipse.org/content/goclipse 


Reference: https://linuxize.com/post/how-to-install-the-latest-eclipse-ide-on-ubuntu-18-04/



### Day 2: Go Language Fundamentals (Packages, variables, and functions)
Learn the basic components of any Go program.

### Day 3: Go Flow control statements: for, if, else, switch and defer
Learn how to control the flow of your code with conditionals, loops, switches and defers.

### Day 4: Go More types: structs, slices, and maps.
Learn how to define types based on existing ones: this lesson covers structs, arrays, slices, and maps.

### Day 5: Go Methods and interfaces
This lesson covers methods and interfaces, the constructs that define objects and their behavio

### Day 6: Go Concurrency
Go provides concurrency features as part of the core language.
This module goes over goroutines and channels, and how they are used to implement different concurrency patterns.

### Day 7: Go TBD
### Day 8: Go TBD
### Day 9: Go TBD
### Day 10: GoTBD

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc


