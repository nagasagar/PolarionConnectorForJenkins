How to use this sample project

1. create a new jenkins job (Free style project)
2. replace config.xml in the new job with the config.xml in this sample project (this requires file system access to jenkins server)
3. under workspace folder (under JENKINS_HOME directory), create a new folder with same name as jenkins job created in first step.
4. un-zip contents maven-project.zip to the folder created above in step 3. 

After this step 4 folder should have src(folder) and pom.xml (file)

5. restart Jenkins

6. edit the configuration of job with actual values for project, xml file location, etc