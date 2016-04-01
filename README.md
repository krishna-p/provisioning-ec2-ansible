## Provisioning EC2 hosts using Ansible

STEPS
=====

Create the following file under your home directory for setting the AWS credentials and add the details.

vim ~/.boto

[Credentials]
aws_access_key_id = your_id
aws_secret_access_key = your_key

Also you need to make necessary changes in the group_vars/.yml file as per your environment.

You can run the playbook using command:

ansible-playbook  provision-ec2.yml
    
