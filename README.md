# Ansible Playbooks
Ansible Palybooks Written and Published by Pramod Sahoo. NO WARRANTY for any damages and loss of data.

# AWS EC2 Instance Creation Using ansible-playbook

Preparing Environment before invoking playbook
To communicate with AWS we are going to use boto / boto3 aws.

  ``$ yum install python python-setuptools ``
  * ansible git curl wget
  
  ``$ curl -O https://bootstrap.pypa.io/get-pip.py ``
  
  ``$ python get-pip.py ``

  ``$ python --version ``
  Python 2.7.5

  ``$ pip --version ``
  
  pip 18.1 from /usr/lib/python2.7/site-packages/pip (python 2.7)

  ``$ pip install boto ``
  
  ``$ pip install boto3 ``

# Follow the Link for YAML File 

- [Spin new ec2 instance](https://github.com/pramodksahoo/ansible/blob/master/EC2/spinawsec2.yml)
- [Terminate existing ec2 instance using instnace id](https://github.com/pramodksahoo/ansible/blob/master/EC2/terminate.yml)
- [Create New Key pair and download keys](https://github.com/pramodksahoo/ansible/blob/master/EC2/createnewkeypair.yml)
- [Delete KeyPair from AWS EC2](https://github.com/pramodksahoo/ansible/blob/master/EC2/removekeypair.yml)

