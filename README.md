# Cloud-Server

Lab 16 AWS

## Task 1

Create a new environment, using Elastic Beanstalk from the AWS Control Panel (GUI)
Manually deploy your application to this environment by uploading a .zip file

[Control Panel Deploy Link](http://lab-16-gui-env.eba-mupzsw5t.us-west-2.elasticbeanstalk.com/)

## Task 2

Using the same server, create a new environment using Elastic Beanstalk from your terminal
Manually deploy your application to this environment by using eb deploy

[Terminal Deploy Link](http://lab-16-terminal-dev.us-west-2.elasticbeanstalk.com/)

### Notes

- Terminal link was just incomplete.
- I got the Gui to deploy by downloading the zip file that the command eb init created. After uploading that file deployment worked, it seems the problem was with my package.json and package-lock.json.

 ![ScreenShot](./img/AWS-Deploy.png)
