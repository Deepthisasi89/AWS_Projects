# AWS Code Pipeline

AWS Code Pipeline builds, tests and deploys code every time there is a change in the source destination which is Github in this case.

## Steps:
  1. Search for Codepipeline in AWS Console
  2. Click on Create Pipeline
  3. Give Pipeline a name and select a new Service Role that allows AWS CodePipeline to create a service role so it can be used with this new pipeline.
  4. Add source stage
     - add Source provider as Github via GitHUb app and setup connection
     - Choose the Repository name under Repository name
     - Set the Default branch as main
     - Choose Next
  5. Add build stage
     - Under command add appropriate build command, for example : `zip Projectsite.zip -r app.py requirements.txt .ebextensions/*`
  6. Skip Test page
  7. Add Deploy stage
     - Choose ElasticBeanstalk as the provider for the deployment by giving the Application and environment name of the [Elastic Beanstalk](/ElasticBeanstalk) as we setup earlier.
  8. Review and Create Pipeline

    
