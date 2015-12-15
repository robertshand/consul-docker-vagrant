# Starts up a consul cluster with three nodes, Each consul 'member' is running in a docker container within the Host VM

## Starting the VM's

    vagrant up

## Starting the consul cluster

    ansible-playbook -i consul_hosts consul.yml