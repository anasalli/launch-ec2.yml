//install ansible ec2 module
ansible-galaxy collection install amazon.aws
//install pip 
yum install pip -u
//install python libraies 
pip isntall boto3 boto botocore
//create IAM user
attach policies directly --> Ec2fullaccess
save access and secret key
//create public and private key in ~/.ssh/ dir
ssh-keygen -t rsa -f ~/.ssh/my_aws
chmod 400 ~/.ssh/my_aws
//access instance
ssh -i "~/.ssh/my_aws" ec2-user@ip
