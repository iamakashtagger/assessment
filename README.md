##CREATING PRODUCTION AND DEVELOPMENT EC2 INSTANCES 

## PRODUCTION INSTANCE DETAILS

- AMI: Ubuntu
- INSTANCE TYPE: t2.micro
- KEY PAIRS: prod-keys.pem
- SECURITY GROUPS:
    - SSH (Port 22) from my IP

# SSH TO IT
sudo -i Downloads/prod-keys.pem ubuntu@Public IP


## DEVELOPMENT INSTANCE DETAILS
- AMI: Amazon Linux 2
- INSTANCE TYPE: t2.micro
- KEY PAIRS: dev-keys.pem 
- SECURITY GROUPS :
  - SSH (Port 22) from my IP

# SSH TO IT
sudo -i Downloads/dev-keys.pem ec2-user@Public IP
