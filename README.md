# Link 

- [http://serve-webap-qjzr9uq6vna3-1418896802.us-west-2.elb.amazonaws.com/](http://serve-webap-qjzr9uq6vna3-1418896802.us-west-2.elb.amazonaws.com/)

# Create Stack
- Network Create `./create.sh networkstack network.yml network-parameters.json`
- Server Create `./create.sh serverstack servers.yml server-parameters.json`

# Update Stack
- Network Update `./update.sh networkstack network.yml network-parameters.json`
- Server Update `./update.sh serverstack servers.yml server-parameters.json`

# Delete Stack
- Network Update `./delete.sh networkstack`
- Server Update `./delete.sh serverstack`