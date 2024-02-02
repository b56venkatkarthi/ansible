# ansible

Ansible is configuration management tool which works both on push and pull mehcanism


### ansible is very famous and is widely used in the industry and its quite popular  want to know the pros of it


1.ansible is agentless software
2.ansible uses ssh as a default mechnaism to communicate to other servers(PORT NUMBER :22)
3.The only thing that anisble node excepts it communication to other servers that needs CM
4.ANSIBLE WORKS BOTH PUSH AND PULL MECHANISM
5.COMMON CEDITAIALS ACROSS THE BOARD (ANSIBLE SERVER SHOULD BE ABLE TO SSH TO ANY OF THE SERVER)
6.ANSIBLE GOES BY DECLARATIVE APPROACH AND THEIR DOCUMENTATION IS REALLLY VAST AND GOOD
7.OPERATIONS ARE PARALLEL WITH ANSIBLE (MULTIPLE CM'S ARE DOABLE )
8.CODE DOESN'T NEED TO BE ON THE TOP OF A LOCAL SERVER !!!

IMPORTANT POINT TO BE NOTED

1.ANSIBLE IN THE ABCKEND USES PYTHON
2.WHEN YOU INSTALL ANSIBLE ,BY DEFAULT IT INSTALLS ANSIBLE VERSION2 WHICH FROM PYTHON
3PYTHON2 IS SUNSET ON JAN2020
4.LATEST VERSION OF ANSIBLE OR VERSION OF ANSIBLE AFTER 2 ARE PYRTHON3 BASED (SO INSTALL ANSIBLE WE NEED TO HAVE PYTHON3)
5.BY DEFAULT ON ALL AWS AMI'S,YOU WILL HAVE PYTHON2 DEFAULT

ANSIBLE ---->REDHAT--->IBM (IBM IS A REDHAT PRODUCT)

INVENTORY IS NOTHING BUT THE LIST OF MACHINE IP OR DNS NAMES THAT YOU WANT ANSIBLE TO BE CHANGED


ansible can be operated in 2 ways

1.manual approach (we can execute one action ata a time)
2.automate approach (we can execute multple acions using playbook)
-----

##Manual Approcah

$ ansible -i inv all - e ansible_user=centos -e ansible_password=DevOps321 -m shell



### widely asked interview question

how to know the list of machies mentioned in the invnetory is up or not


$ ansible -i inv all -e ansible_user=centos -e ansible_password=DevOps321 -m ping


what is playbook

on high level playbook is an ansible script to execute things parallely

A PLAYBOOK IS LIST OF PLAYS

a play is list of tasks

a task is an action that we want to execute

what is the language used by playbook

YAML is the languagae used by ansible to write playbooks


what is markup language

markup language is a presentation langauage

ex :HTML , XML 

