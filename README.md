# ansible-gcp-cf-one
create and access cloud functions using ansible

#### Setup Ansible :

	$ sudo pip install ansible

#### Add the secret key JSON:
	
	- Create service account, give admin permission and create a JSON key and keep the json key in parent directory.

#### Check the syntax using command :
	
	$ ansible-playbook playbook.yaml --syntax-check

#### Run the playbook using command :
	
	$ ansible-playbook playbook.yaml