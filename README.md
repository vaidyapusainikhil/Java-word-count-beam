# Java-word-count-beam

Set up your development environment

1. Download and install the Java Development Kit (JDK) version 8, 11, or 17. Verify that the JAVA_HOME environment variable is set and points to your JDK installation.

2. Download and install Apache Maven by following the installation guide for your operating system.

3. Optional: If you want to convert your Maven project to Gradle, install Gradle.

Get the example code

1. Generate a Maven example project that builds against the latest Beam release:

     mvn archetype:generate 
     `
    -D archetypeGroupId=org.apache.beam `
  
    -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
  
    -D archetypeVersion=2.42.0 `
  
    -D groupId=org.example `
  
    -D artifactId=word-count-beam 
  `
    -D version="0.1" `
  
    -D package=org.apache.beam.examples `
  
    -D interactiveMode=false
  
  Maven creates a new project in the word-count-beam directory.
  
  2. Change into word-count-beam:
  
    cd .\word-count-beam
   
  The directory contains a pom.xml and a src directory with example pipelines.
  
  3. List the example pipelines:
  
    dir .\src\main\java\org\apache\beam\examples
   
