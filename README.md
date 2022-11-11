# Getting Started Website Stack 


## Cycle Stacks
The file in this repo named `cycle.json` is a [Cycle stack file](https://docs.cycle.io/docs/stacks/writing-a-stack-file).  It contains infromation usable by Cycle to create 1 or more container images and can be used to deploy those images in a group to a new or existing [Cycle environment](https://docs.cycle.io/docs/environments/overview). 


## Whats In This Stack?

### Version 
The `version` is the version of the Cycle Stack Spec (currently 1.0).

### Containers 
Inside containers a stack file will have 1 or more container records.  This starts with the container identifier as the key and the container object as the value. 

### Image
The image object holds information about the container image, its type, and where Cycle should look to import it from.  For the stack located in this repository, its using `docker-hub` to target the `cycleplatform/getting-started` container with the tag `latest`.  


### Config
The configuration section gives users granular control over their containers network, runtime, deployment, resource, and integrations settings.  In the example from this repo there are custom settings for network and deploy.  

To learn more about Cycle stacks visit our [documentation](https://docs.cycle.io/docs/stacks/overview) or come ask us some questions in our [community Slack channel](https://slack.cycle.io).  

