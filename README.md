Maven Archetypes
========================

Description
------------------------
This project helps to create a multi-module maven project. It contains the following archetype. 
1. parent -- This is the parent project, it also creates a common module in the root parent. 
2. exectable-jar -- this is a submodule which creates fat executable jar.    

The following plugin and frameworks are pre configure. 
1. Spring Boot 
2. jacoco 
3. findbug 
4. testng
5. equalsverifier
6. mockito
7. checkers-quals
8. checkstyle
9. enforcer
10. pmd
11. cobertura
12. antrun
13. pojomatic
14. spring test framework
 
Usage: 
---------------------------
parent project:
---------------------------
mvn archetype:generate -DarchetypeGroupId=com.archetype -DarchetypeArtifactId=mvn-archetype-parent -DarchetypeVersion=1.0 -DgroupId=<project group id> -DartifactId=<project artifact Id>

executable-jar: 
---------------------------
mvn archetype:generate -DarchetypeGroupId=com.archetype -DarchetypeArtifactId=executable-jar -DarchetypeVersion=1.0 -DgroupId=<submodule group id> -DartifactId=<submodule artifact Id>

jpa
---------------------------
mvn archetype:generate -DarchetypeGroupId=com.archetype -DarchetypeArtifactId=jpa -DarchetypeVersion=1.0 -DgroupId=<submodule group id> -DartifactId=<submodule artifact Id>



