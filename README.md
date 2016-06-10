# launch-openstack-instances

## How to use

- Create a file with credentials (clouds.yml). **clouds.yml.sample** is an example. 
- Copy SSH key (id_rsa.pub).
- Set the variables (var.yml).
- Run the playbook:
  `ansible-playbook create.yml`
  
Note: The verification of the ssh port uses a private network
