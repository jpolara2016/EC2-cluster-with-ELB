# EC2-cluster-with-ELB


This playbook can be used to provision resources in AWS. It will set up a cluster with multiple instances in each subnets, and register all newly launched instances with ELB.

## Requirements:
You need Python3 & boto3 installed on you local machine.

## Commands:
1. Change the current working directory.
```
cd /Users/jpolara/Desktop/aws_cluster 
```

2. You must replace Access & Secret key with your own keys.
```
export AWS_ACCESS_KEY_ID=AKIAUQLBEPfhkjhkdskVAMFPVPPC
export AWS_SECRET_ACCESS_KEY=Dhc/rLx2qfhaksjhdkasjY695/FPOMIQivRYGKqniOeqcBF1y+W

ansible-playbook -i host cluster.yml -vv
```

