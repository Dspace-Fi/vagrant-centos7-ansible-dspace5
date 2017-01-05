Ansible provisioned Vagrantfile for DSpace
==========================================

This is an Ansible provisoned Vagrantfile for DSpace 5 (currently 5.6). It is author's first attempt in writing ansible playbooks and can probably be improved in many ways. Also, much of the configuration is hardcoded in template files and should be moved into playbook etc.

You will need ansible (version used was 2.2), vagrant and vagrant box named centos7 (you can create one with packer from this repository: https://github.com/isido/packer-centos-7 [note that you might have to update CentOS image checksums and names] or you could use other ready made boxes from here https://atlas.hashicorp.com/boxes/search).