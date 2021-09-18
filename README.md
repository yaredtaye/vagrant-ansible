## VM provisioner using vagrant and ansible

* Vagrant supports multiple virtualization drivers which includes hyperv, virtualbox, kvm, vmware...
* You can specify the underlying preffered driver as part of configuration. Refer inventories/hostvars/spec.yml 
* Number and specifications for each VM are set as host variables. Refer inventories/hostvars/spec.yml


### RUN Script

```
$ ansible-playbook  -i hosts.ini site.yml

