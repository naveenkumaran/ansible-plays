## Collection of ansible scripts to provision my cluster for demo.

# Create user and group

# Provisioning a K8 cluster using kubespray
* Provisioner is customized for deploying 1 master and 2 nodes as workers
* Job scheduler will be enabled in master 
* Local storage is used as a volume provisioner
'''java Clone kubespray and run the following command
 ansible-playbook -i ../k8-cluster/inventory --become cluster.yaml
'''
 
