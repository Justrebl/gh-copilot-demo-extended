run the following commands to get you started : 

```bash 
curl https://start.spring.io/starter.zip \
           -d dependencies=web,devtools \
           -d bootVersion=3.1.5 \
           -d type=maven-project \
           -d applicationName=CopilotSample \
           -d packageName=com.microsoft.sample \
           -d groupId=com.microsoft.sample \
           -d artifactId=CopilotSample \
           -o my-project.zip

unzip my-project.zip
```