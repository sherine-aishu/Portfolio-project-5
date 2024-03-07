# Portfolio-project-5
End-to-End Python Application Deployment using Docker and GitHub Actions

**Project Overview**

*Initially, the Python application is tested locally in the developer environment. Following this, the application is containerized using Docker and tested locally once again. If all tests pass, the code is then pushed to the GitHub repository. This action triggers two workflows: the first workflow is responsible for building and pushing the Docker images to Docker Hub, while the second workflow pulls the Docker image and deploys the application on production servers. Prior to triggering these workflows, the setup of production servers and the authentication between GitHub and the production servers are completed. Once everything is set up correctly, the application running on the production servers can be accessed from the internet.*

**STEPS**

            
                Step 1: Setting up developer environment

                Step 2: Running our application locally
                
                Step 3: Accessing our locally hosted application via internet
                
                Step 4: Containerising our application
                      a. w/o using requirements.txt 
                      (or)
                      b. using requirements.txt
                
                Step 5: Pushing the application code to Github repository
                     a. Installing git
                     b. Authenticating to git from local 
                     c. Pushing code to git repository
                 
                Step 6: Setting up the production servers
                
                Step 7: Creating Workflows for deployment
                     a. Workflow 1 for build and push
                     b. Set up authentication in GitHub to access our production servers
                     c. Workflow 2 for pull and run
                
                Step 8: Accessing your python application
        
          

