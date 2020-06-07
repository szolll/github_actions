# Github actions

Example of github actions... in action. 

# Configuration

In your github root create a folder structure as listed below and add the flow. 
The name of the file doesn't matter as long as it ends with .yml or .yaml

/.github/workflows/YOUR_FILE_HERE.yml

You'll have to create some github secrets for this to work, you could hardcode your docker credentials, but thats not the smartest thing one can do ;)

Create the following secrets

 DOCKER_USERNAME 
 - your docker registry credentials
 
 DOCKER_PASSWORD 
 - .......
       
 TWILIO_PHONE_NUMBER 
 - Your Twilio Phone number (Twillio provides free credits for new users)
 
 MY_PHONE_NUMBER  
 - The phone number we want to inform when our build fails

 TWILIO_ACCOUNT_SID
 - Provided by Twillio
 
 TWILIO_API_KEY 
 - Provided by Twillio
 
 TWILIO_API_SECRET 
 - Provided by Twillio
     
# Usage
As a example, change the file itself and push it to master... Browse to github.com browse to the actions tab in your repo and the action should be running. 
 
