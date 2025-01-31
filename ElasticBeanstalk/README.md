# AWS Elastic Beanstalk

AWS Elastic Beanstalk as the deployment target for our sample application and GitHub as the source location.

1 Creating the deployment traget.
  - Select Elastic Beanstalk from the AWS Console and click on it.
  - If you have no applications running, click on “Create application”.
  - Give the application a Name, in this case "Projectsite", description (optional) and Tags(optional) then click “Create”
  - Create an environment for your application, by cliking on “Create new environment”
  - Create the environment by choosing the platform as Python and uploaded the code as a local file.
  - Create and use new service role, choose a EC2 key pair and  an IAM instance profile with managed policies that allow your EC2 instances to perform required operations.
  - Leave all the other options to default and Skip to review
  - Submit
  - Once created, click on the domain name to see your web page.
 
 
