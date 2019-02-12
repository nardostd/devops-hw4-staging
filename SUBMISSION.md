# SE441-HW4
## Nardos Tessema
## ID\#: 1941511

## Ant+Ivy [40 pts]
```
$ant -version
$echo $ANT_HOME
```
![$ANT_HOME & ant -version](images/ant-v.png)
```
$ant go-nodeps
```
![ant go-nodeps](images/ant-go-nodeps.png)
```
$ant
```
![successful build](images/ant-successful.png)
```
$java -jar target/hello-world-all-1.0-SNAPSHOT.jar
```
![Successful Execution](images/java-jar-ant.png)
#### Links to build\.xml and ivy\.xml
* [hello-world/build.xml](hello-world/build.xml)
* [hello-world/ivy.xml](hello-world/ivy.xml) files.

## Maven [30 pts]
```
$mvn -v
```
![mvn -v](images/mvn-v.png)
```
$mvn clean package
```
![BUILD SUCCESS](images/mvn-clean-package.png)
```
$java -jar target/hello-world-1.0-SNAPSHOT-jar-with-dependencies.jar
```
![Successful Execution](images/java-jar-mvn.png)
#### Link to pom\.xml
* [hello-world/pom.xml](hello-world/pom.xml)

# Gradle [30 pts]
```
$gradle -v
$which gradle
```
![Gradle Home and Version](images/gradle-v-which-gradle.png)
```
$gradle clean fatJar
```
![BUILD SUCCESSFUL](images/gradle-clean-fatJar.png)
```
$java -jar build/libs/hello-world-all-1.0-SNAPSHOT.jar
```
![Successful Execution](images/java-jar-gradle.png)
#### Link to build\.gradle
* [hello-world/build.gradle](hello-world/build.gradle)
