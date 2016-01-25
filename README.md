# openapphack-ansible-roles

Openapphack Ansible Roles is a list of ansible roles that can be used in any of the openapphack projects

List of validated ansible roles that you can use in your openhack project is [here](https://github.com/WiproOpenSourcePractice/openapphack-ansible-roles/blob/master/validated-openapphack-ansibleroles.md)

If you need an ansbile role for your openapphack project please follow the next set of instructions.

# How to add a new ansible role to the validated list of openapphack ansible roles?

You will have to follow the step given below

1 . Create your ansible roles . Follow instructions as mentioned in the [here](https://galaxy.ansible.com/intro#create-role)  

2 . Create a github repository that follows the naming convention ansiblerole-openapphack-{rolename}

3 . Create an openapphack project and integrate your ansible role to the [openapphack project](https://github.com/WiproOpenSourcePractice/openapphack-vm). 

4 . Integrate and test your ansible role with [openapphack-vm](https://github.com/WiproOpenSourcePractice/openapphack-vm)

5 . Make an entry in the openapphack-ansible-roles.md file with your new ansible role name .
Submit a pull request to [openapphack-ansible-roles](https://github.com/WiproOpenSourcePractice/openapphack-ansible-roles) to include your ansible role to the list of openapphack ansible roles.

Mention your openapphack project github url as the project is using the new role.

6 . An openapphack reviewer will try out your openapphack project and include it to the list of [validated openapphack-projects]().  All your validated ansible roles will be add to the list [here] , Similiarly if you have yoeman generators they will be include in the list [here]() 



