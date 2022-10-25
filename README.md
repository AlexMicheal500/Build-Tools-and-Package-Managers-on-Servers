# Build-Tools-and-Package-Managers-on-Servers
Application needs to be deployed on a production server
For that, we want to package application into a single moveable file (artifact), also
called "building the code"
This is what a build tool or package manager tool does

SPECIAL THANKS TO NANAWORLD

![image](https://user-images.githubusercontent.com/99332618/197706658-947ebbed-f62d-4eb4-b83e-62365dff1efe.png)

Build an Artifact
They are used to: 
1. Install dependencies
2. Compiles and compress codes
Example Build Tools for Java: Gradle and Maven
Artifact: JAR or WAR file respectively.
Dependencies in gradle are store in:
Gradle: Configuration is stored in XML
Maven: Configuration is stored in Groovy

Build JavaScript applications
Artifact of a JavaScript application is e.g. a zip or tar file
But no special artifact type defined
In JS we have package managers and NOT
build tools
For JS we have npm and yarn
package.json file for dependencies
Package manager install dependencies, but
not used for transpiling JS code
![image](https://user-images.githubusercontent.com/99332618/197712755-0483511b-7f0e-4955-ba0f-75d925877717.png)
![image](https://user-images.githubusercontent.com/99332618/197712887-0f6710f5-6506-4e90-8112-f0f129eb4849.png)
![image](https://user-images.githubusercontent.com/99332618/197712959-808035b5-84cc-45a9-ae7e-5e84234db906.png)
![image](https://user-images.githubusercontent.com/99332618/197713176-690e59b1-3a86-433f-90db-514c968383fd.png)
Why should you know these Build Tools as a DevOps engineer?
Help developers building the application, because you know where and how it will run on deployment servers.
You need to configure the build automation tool or CI/CD Pipeline,
like execute tests on the build servers, build and package into Docker Image,
run the application on server.
![image](https://user-images.githubusercontent.com/99332618/197713701-73758276-4e08-47b1-9e31-8dc3a8e75756.png)
![image](https://user-images.githubusercontent.com/99332618/197714678-226baba3-9fd2-4399-bcd5-ae522096b430.png)
![image](https://user-images.githubusercontent.com/99332618/197715034-554a33ef-7a31-4463-9821-02f161746d1f.png)
![image](https://user-images.githubusercontent.com/99332618/197715154-c97b85ec-f64b-4a2a-9cdf-68720afe38e6.png)
![image](https://user-images.githubusercontent.com/99332618/197715373-b2c25d2f-cf0f-4e9c-99e5-70fed327e8ae.png)
![image](https://user-images.githubusercontent.com/99332618/197715462-fb8e9216-9f88-47b2-89b1-fc117dc5bab0.png)



