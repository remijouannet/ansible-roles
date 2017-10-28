ansible-roles
==================
ansible roles i reuse for every project

most of it are for Centos some for debian (and other for both)

List of roles
------------

* ansible : just install ansible
* common : upgrade everything, install a few packages, set hostname to the inventory_hostname
* docker : install docker 
* fs : format and mount a volume
* grafana : install grafana and configure one Datasource for prometheus
* haproxy : install haproxy, install backend/frontend for http and https
* ioquake3 : install ioquake3 dedicated server
* iptables : push iptables-restore file and execute it
* jenkins/master : Install Jenkins and configure the following : admin password, email, plugins, one seed job that use DSL jobs
* jenkins/slave : Install jenkins slave
* mongodb : install mongodb, configure admin password
* mysql : install mysql 5.7, create databases with associate users
* nginx: install nginx and push custom configuration
* nodejs : install nodejs 6
* openvpn : install openvpn as a server, only work with systemd
* prometheus/prometheus : install prometheus server with a custom configuration
* prometheus/node_exporter : install node_exporter with a custom configuration
* python27: install a few packages for python27 on debian/ubuntu
* python34: install a few packages for python34 on debian/ubuntu
* rabbitmq: install rabbitmq with a vhost/user
* redis : install redis without custom configuration
* supervisor : install supervisor with custom jobs
* ufw : install ufw and allow the tcp port 22
* users : create sudo group, create users, push pub ssh key for each users 
