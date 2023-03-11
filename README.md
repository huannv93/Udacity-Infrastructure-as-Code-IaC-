# Udacity-Infrastructure-as-Code-IaC-

### Project :
In this project, you’ll deploy web servers for a highly available web app using CloudFormation. You will write the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. You will begin with deploying the networking components, followed by servers, security roles and software

There will be two parts to this project:

- Diagram: You'll first develop a diagram that you can present as part of your portfolio and as a visual aid to understand the CloudFormation script.
- Script (Template and Parameters): The second part is to interpret the instructions and create a matching CloudFormation script.




### How to run the the code?
```bash
# Ensure that the AWS CLI is configured before runniing the command below
# Check the region and profile AWS CLI in the script file

# Create the network infrastructure first!
./create.sh myNetwork network.yml network-parameters.json

# Create servers
./create.sh myServers servers.yml server-parameters.json

#update stack:
./update.sh mySecStack servers.yml server-parameters.json
```
