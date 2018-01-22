# Ansible Role: ECS-Cluster 

Creates AWS ECS Cluster

## Requirements

- boto<br />
- boto3<br />
- python >= 2.6

## Role Variables

Available variables are listed below, along with default values:
 
 
## The defaults provided by this role which are mandatory

- ecs_cluster_name<br />
- ec2_launch_configuration_name<br />
- key_name<br />
- ec2_security_groups<br />
- ec2_asg_vpc_subnets<br />
- ec2_instance_type<br />
- ec2_asg_availability_zones<br />
- ec2_ami_id<br />
- ec2_instance_name<br />
- vpc_name<br />
- ecs_state<br />

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
 
