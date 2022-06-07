## Deploy a Highly-Available Web App using CloudFormation

### [Live Link](http://serve-webap-45mrl2yhsgab-1411785819.us-west-2.elb.amazonaws.com/)

### Architecture Diagram
![Architecture design](images/Udagram-diagram.png)

### Files 

* network.yml & network-parameters.json ====> Creates/updates the network Stack
* servers.yml & server-parameters.json =====> Creates/updates the server Stack

### Scripts
* ./create.sh ======> Creates the new stack

* ./update.sh ======> Updates an existing Stack

* ./delete.sh ======> Deletes an existing stack

### Successful Deployed Stacks
![Server STACK CREATION SCRIPT](images/stacks.png)

### Target Group With Healthy Instances
![Server STACK CREATION SCRIPT](images/targetgroups.png)

### Running Instances
![Server STACK CREATION SCRIPT](images/instances.png)

### Testing Our Link In The Browser
![Server STACK CREATION SCRIPT](images/websuccess.png)
### [Live Link](http://serve-webap-45mrl2yhsgab-1411785819.us-west-2.elb.amazonaws.com/)
