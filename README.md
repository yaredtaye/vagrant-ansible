## VM provisioner using vagrant and ansible

* Vagrant supports multiple virtualization drivers which includes hyperv, virtualbox, kvm, vmware...
* You can specify the underlying preffered driver as part of configuration. Refer hostvars/<hostname>.yml 
* Number and specifications for each VM are set as host variables. From this vagrant file is created dynamically as per each host based on vagrant template. Refer hostvars/<hostname>.yml, role/vagrant/template


### RUN Script

```
$ ansible-playbook  -i hosts.ini site.yml

