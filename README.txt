 ## Cloud DevOps Engineer Nanodegree Project_2 - Deploy a high availability web app using CloudFormation
This project makes available the following:

### The Infrastructural Diagram 
1.  https://www.lucidchart.com/documents/edit/820d76b6-1d16-497e-bfd0-ed4b41308504/0_0 is the URL of the infrastructural diagram.
2.  udagramapp infrastructural diagram.PNG is the snapshot of the infrastructural diagram. 

### The CloudFormation scripts interpreting the infrastructural diagram
1.  udagramIAM - this is the script for the IAM role that allow my instances to access s3 bucket.
2.  udagramIAMparams.json - this is the parameter file for the IAM Role.
3.  udagraminfra-servers.yml - this is the script for the servers and their properties.
4.  udagraminfra.yml - this is the script for the network components.
5.  udagramparams-servers.json - this the parameter file for the servers.
6.  udagramparams.json - this is the parameter file for the networking components.

### Loadbalancer URL
The DNS name of the loadbalancer is udagr-WebAp-ULKNRV9QPTJF-1455523920.us-west-2.elb.amazonaws.com