---
title : "Temporal Setup"
weight : 51
---


##### Install the Temporal CLI with cURL

        curl -sSf https://temporal.download/cli.sh | sh

##### Choose a development Cluster

Which development Cluster should you choose?

We recommend choosing a development environment based on your requirements.The source code for the Temporal Server (the orchestrating component of the Temporal Cluster) is licensed under the MIT open source license. So, in theory, anyone can take the Temporal Server code and run their Temporal Platform in any number of creative ways. However, for most developers we recommend starting by choosing one of the following:
- Local development server
- Temporal Cloud
- Self-hosted Temporal Cluster

##### How to start a local development server

If you have successfully installed the Temporal CLI, open a new terminal and run the following command:

        temporal server start-dev --db-filename temporal.db

This command automatically starts the Temporal Web UI, creates a default Namespace, and creates a persistence database. For more command details and options, see the CLI reference

The Temporal Web UI serves to http://localhost:8233.

##### How to start temporal server on Docker
        sudo curl -L https://download.docker.com/linux/centos/7/x86_64/stable/Packages/docker-compose-plugin-2.6.0-3.el7.x86_64.rpm -o ./compose-plugin.rpm

        sudo yum install ./compose-plugin.rpm -y

To find the Server URL, 
        navigate to EC2 instance and get the public IP address of the EC2 instance attached to cloud9.
        
        Navigate to Security group of the EC2 and add an inbound rule for 
        Custom TCP      Port:8080

##### How to create a Namespace on the development server

The development server does automatically create a default Namespace (named "default") when it starts up. However, you will create a custom one for our application. Since this is something recommended at a production level, it's recommend practicing it with the development server.

Use the temporal operator namespace create command using the Temporal CLI to create a Namespace on the development server.

        alias temporal_docker="docker exec temporal-admin-tools temporal"

        temporal operator namespace create backgroundcheck_namespace