# spring-app-maven


The maven build steps involved are as follows

**mvn validate** - It calidates if all the files in projectare present or not

**mvn compile** - It compiles the project source code and generates the target folder

**mvn test** - It runs the unit test cases (if there are) against the compiled source code.

**mvn package** - It packages the comipled code into the distributed format like **jar/war/ear**

**mvn install** - It will install the package into the local repository named as *.m2 folder*

**mvn deploy** - using this we can push our artifact into the artifactory repository eg Nexus etc.

# Other commands that can be used

**mvn clean** - It would completely remove the target folder completely

**mvn clean package** - It would firstly remove the target folder and would generate a completely new target folder


# How to execute the Java Project ?

```
java -jar target/spring-boot-web.jar
```

![Screenshot from 2023-06-01 11-56-47](https://github.com/adityadhopade/spring-app-maven/assets/48392204/cc561b1e-b90f-42f3-9474-2cdfd5e8221a)
