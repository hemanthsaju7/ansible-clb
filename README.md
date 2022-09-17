# ansible-clb
Ansible playbook to setup classic load balancer with http to https redirection. 

Here I'm creating 3 ec2 backend instances using ansible along with a key pair, security group, classic load balancer and 
also creating alias record in route53 in the first play.

In the second play, I'm setting up apache webserver by cloning a demo php website from github to the doc root of the backend instances.
