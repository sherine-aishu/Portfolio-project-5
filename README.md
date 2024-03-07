# Portfolio-project-5
End-to-End Python Application Deployment using Docker and GitHub Actions

**STEPS**

Developer develops the code 
Test it locally
Push it to GitHub
Once reviewed , merged to master
WF ensure the docker image built is pushed to docker hub and the same is pulled by our prod servers and containers are started
WF1 should be triggered if the pull request towards master is closed 
WF1 builds the docker image and push it to docker hub
WF2 if WF1 is successful, then the same image needs to be pulled by prod server and run the container using that image which makes up our app 

    
            
            
                Step 1: Setting up developer environment

                Step 2: Running our application locally
                
                Step 3: Accessing our locally hosted application via internet
                
                Step 4: Containerising our application
                      a. w/o using requirements.txt
                      b. using requirements.txt
                
                Step 5: Pushing the application code to Github repository
                 
                Step 6: Setting up the production servers
                
                Step 7: Creating Workflows for deployment
                
                Step 8: Accessing your python application
        
          

