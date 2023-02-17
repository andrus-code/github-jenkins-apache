# Why Integrate Github + Jenkins 

You should integrate Jenkins and GitHub to improve the efficiency of building, testing, and deploying your code. 
The integration presented in repo will teach you how to schedule your build, pull your code and data files from your GitHub repository to your Jenkins machine, and automatically trigger each build on the Jenkins server after each Commit on your Git repository.
But first, let’s configure the Jenkins and GitHub integration. Let's begin with the GitHub side!
Jenkins is server in my house and need to connect it with github, for that I need to open 8080 in my router and I need to configure Webhooks in github


####  Configuring Github

1. Go to your Github repository and click on "Settings"

![](images/1.png "Seetings")

2. Clock in Webhooks and then click 'Add webhook'

![](images/2.png "Webkooks")

3.  In the ‘Payload URL’ field, paste your Jenkins environment URL. At the end of this URL add /github-webhook/. In the ‘Content type’ select: ‘application/x-www-form-urlencoded’ and leave the ‘Secret’ field empty.

![](images/3.png "Payload URL")

####  Configuring Jenkins







