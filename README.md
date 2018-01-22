# Ansible Role: ECS-Cluster 

Creates AWS ECS Cluster

## Requirements

boto
boto3
python >= 2.6

## Role Variables

Available variables are listed below, along with default values:
 
 
## The defaults provided by this role which are mandatory

ecs_cluster_name
ec2_launch_configuration_name
key_name
ec2_security_groups
ec2_asg_vpc_subnets
ec2_instance_type
ec2_asg_availability_zones
ec2_ami_id
ec2_instance_name
vpc_name
ecs_state
Set these defaults according to your infrastructure.

## Dependencies

None.

## Example Playbook (installs zabbix-server version 3.0 and above)
 
 
- hosts: localhost
  roles:
    - aws-ecs

License

MIT / BSD

Author Information

www.opstree.com

blog.opstree.com
Contact GitHub API Training Shop Blog About
 
