# Service Project

Testinium supports Karate, Java, Gauge and Cucumber frameworks for service testing.

For the framework you want to run, a Service project is created with the Create New Project steps from the Project screen.



**Service Karate**

There should definitely be one java class in the service test written with Karate.

![](<../.gitbook/assets/image (57).png>)

Cucumber steps should be in the src->resources->features directory.

![](<../.gitbook/assets/image (14).png>)



**Java Service**

In Java service tests, no action different from what is known is required. The Java service test, which is written, can be run as it is written.

![](<../.gitbook/assets/image (7).png>)

**Cucumber Service**

It should be the same as a normal cucumber project. There should be a Cucumber Runner class and feature files should be under src->resources->features folder.

![](<../.gitbook/assets/image (52).png>)

**Gauge Service**

In projects created with **Selenium-gauge**, what should be in the project;

\-Projects created with selenium-gauge must have unique tags.

![](<../.gitbook/assets/image (37).png>)

\-manifest.json file must contain xml report.

![](<../.gitbook/assets/image (56).png>)

\-.gitignore file should be in the project.

\-Target file should not be pushed to remote repository

### ****
