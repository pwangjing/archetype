Maven Archetypes
========================

#Description
This project helps to create a multi-module maven project. It contains the following archetype.  
1. parent -- This is the parent project, it also creates a common module in the root parent.   
2. exectable-jar -- this is a submodule which creates fat executable jar.      

#The following plugin and frameworks are pre configure. 
-  Spring Boot   
-  jacoco   
-  findbug   
-  testng   
-  equalsverifier  
-  mockito  
-  checkers-quals  
-  checkstyle   
-  enforcer   
-  pmd   
-  cobertura    
-  antrun   
-  pojomatic   
-  spring test framework   
 
#Usage 
##parent project:
mvn archetype:generate -DarchetypeGroupId=com.archetype -DarchetypeArtifactId=mvn-archetype-parent -DarchetypeVersion=1.0 -DgroupId=<project group id> -DartifactId=&lt;project artifact Id&gt;

##executable-jar: 
mvn archetype:generate -DarchetypeGroupId=com.archetype -DarchetypeArtifactId=executable-jar -DarchetypeVersion=1.0 -DgroupId=<submodule group id> -DartifactId=&lt;submodule artifact Id&gt;

##jpa:
mvn archetype:generate -DarchetypeGroupId=com.archetype -DarchetypeArtifactId=jpa -DarchetypeVersion=1.0 -DgroupId=<submodule group id> -DartifactId=&lt;submodule artifact Id&gt;



