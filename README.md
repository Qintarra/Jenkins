# Jenkins  

Test projects for Git training

Build
=======
Java project:
Tested on [17.0.4.1](https://www.oracle.com/java/technologies/downloads/#jdk17), [Maven 3.8.6](http://maven.apache.org/download.cgi) and [Jenkins 2.364](https://get.jenkins.io/war/2.364/)
```
mvn clean test
```

.NET project: latest version of [.NET Core 3.1](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) should be installed.

After installation execute the following command:
```
dotnet build Calculator.sln
```