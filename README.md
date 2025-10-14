# intro-to-ansible-lab-files


Starter files for the intro to Ansible Lab, 4640.

Read lab instructions on D2L


## Commands (Put commands in code blocks and include a brief description of each command.)
- create new keys
`ssh-keygen -t ed25519 -f ~/.ssh/aws`
- Run included scripts to import and delete keys
1. modify the file permission `chmod +x import_lab_key`
2. Run the script to import the key to aws`./import_lab_key /home/laraa/.ssh/aws.pub`
3. Run the script to delete the key: `./delete_lab_key `

- terraform commands (init, fmt, validate, plan and apply)
1. `terraform init`:Initializes a working directory with Terraform config files 
2. `terraform validate`: validate the syntax
3. `terraform plan`: have a dry-run
4. `terraform apply`: deploy the infrastructure
- ansible commands

## A screenshot of the rendered html page from one of your servers
