
# Prerequisite
 - You should have keycloak downloaded before you can run keycloak.
 - You should have your JAVA_HOME set in path to run java -jar command

# How to run this project
1. Build the project - On command line from project directory
 - gradlew clean build

2. Build command will create a executable jar file in ./build/libs directory
 - cd build/libs

3. Run the application
 - java -jar todolist-0.0.1-SNAPSHOT.war

4. Open another command line window to run keycloak application -
 - standalone.bat -Djboss.socket.binding.port-offset=100

5. Launch the application in browser
 - https://localhost:8743/login

6. Click the button 'Login with Keycloak SAML'. This will take you to keycloak login screen.

7. Enter credentials.
   username - sam.doe@gmail.com
   password - test123

8. You will be logged in and you will see To-Do List.
