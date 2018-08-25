
# CONFIG-SERVER
Java Springboot application as a config server.
Config-value : https://github.com/langitdsp/config-value.git
Config-client : https://github.com/langitdsp/config-client.git

## Getting Started
This application will get the config value from git repository.
This application will run on port 8888

#### Setup Your Local :
Edit your config source at

    src\main\resources\application.properties
    spring.cloud.config.server.git.uri=https://github.com/langitdsp/config-value

To run this application : mvn spring-boot:run
Access the application on http://localhost:8888/config-value/default to get the config value.

