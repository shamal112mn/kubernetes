# kubernetes

'''
Run 1
terraform-deploy-gke - > gke-cluster contains terraform code to create cluster

1. create backend storage for terraform
2. update cluster.tfvars file with backend
3. run: source set_env.sh cluster.tfvars to init terraform
4. terraform apply --var-file=cluster.tfvars

Run 2
terraform-deploy-gkke -> common-tools contains cluster updates

1. use backend storage for terraform
2. update common-tools.tfvars file with backend
3. run: source set_env.sh common-tools.tfvars to init terraform
4. terraform apply --var-file=common-tools.tfvars


'''
