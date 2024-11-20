# Polarion Plugin For Jenkins

## How to run jenkins in dev environment

In order to run this plugin with jenkins 
- Import this project to eclipse as a maven project
- run command `mvn clean hpi:run` 


## How to build plugin for distribution

- run command `mvn clean hpi:run`
- run command `mvn hpi:hpi`
- for more information on different goals available refer [maven-hpi-plugin Documentation](https://jenkinsci.github.io/maven-hpi-plugin/plugin-info.html)

This will create a `PolarionPlugin.hpi` under `target` folder.

## How to install plugin in jenkins

- navigate to *Manage Jenkins* > *Plugins* > *Advanced Settings* > *Deploy Plugin*
- upload the plugin (`.hpi` file) and click on **Deploy** button
- restart jenkins.