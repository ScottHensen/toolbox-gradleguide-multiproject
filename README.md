# Template Multi-Project Gradle Build
This template is the result of the Gradle Guide found here:
  https://guides.gradle.org/creating-multi-project-builds/

### Project Structure:
- multi-project-gradle  
   builds the whole project   
   - greeter  
      builds tar/zip files from groovy app  
   - greeting-library  
      builds jar file from java app  

### How to build:
- Build the whole project:  
   /multi-project-gradle> gradlew build          

- Build just one of the sub-projects:  
   /multi-project-gradle> gradlew :greeter:build  
   -or-  
   /multi-project-gradle/greeter> gradlew build  
