# AWS Bootstrap

Simple way to bootstrap your AMI using Ansible

CF templates requires `ansible-city.aws_foundation` stacks to be present.
Alternatively you can make sure that the following CF Outputs are present:

* <ENV>-vpc-VpcID
* <ENV>-vpc-SubnetsPublic
* <ENV>-vpc-SubnetsPrivate
