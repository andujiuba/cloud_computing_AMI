### Building AMIs

- create AMIs of instances and stop/terminate instance and running state
- want AMI to have mongobd installed
- click instance, actions, image, create image --> name and description: sre_akunma_*instance name*_ami
- sleect AMI click LAunch and use same settings as instance (choose existing security group)

in gitbash: ssh -i "sre_key.pem" ***ubuntu***@ec2-54-228-85-20.eu-west-1.compute.amazonaws.com

- add app_ami ip to security port for db
To Research:

- What is an AMI?

AWS introduction - EC2 instances - Security groups-inbound and outbound rules,  - step by step guide how to deploy 2tier app on aws, building AMIs
