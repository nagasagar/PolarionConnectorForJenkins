Installation
This is a plugin that can be installed on Jenkins
1.	navigate to Manage Jenkins > Plugins > Advanced Settings > Deploy Plugin
2.	upload the plugin (.hpi file) and click on Deploy button
3.	restart jenkins.

Setup

This plugin uses Rest API to communicate with polarion. SO, personal Access token is to be generated and used for creating connection. Make sure permissions to use Rest API are assigned to the user.
Configure connection to polarion.
1.	Navigate to Manage Jenkins > System 
2.	Find section Polarion Connector, and enter
a.	Polarion Rest URL
b.	Token
3.	Verify the connection by clicking on “Test Connection”

Using Polarion Work Item Status Updater
After successful installation of plugin, a new build step should be available while configuring Jenkins job.
Parameters could be either hard coded or can be configured to use one of Jenkins build parameters

Using Polarion Test Reporter
After successful installation of plugin, a new post-build action should be available while configuring Jenkins job.
For a Jenkins job which generates test results in x-unit format, it can be configured to create a test run in polarion automatically to publish test results to polarion.
Up on successful completion of Jenkins job a test run created.

Note :
Sources of this plugin are available in src.zip
sample jenkins job illustrating the usage is present in Sample-Jenkins-Job.zip 