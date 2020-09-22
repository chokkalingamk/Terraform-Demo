#####################################################################
#             BrainStack DevOps-Zabbix Lab Setup                    #
#             Version:v2.1                                          #
#             Auther: ANAND A U                                     #
#             VM OS Image : Ubuntu 16.04 LTS and CentOS7            #
#####################################################################
#Zabbixserver configuration
Vagrant.configure(2) do |config|
  config.vm.define "ubuntuvm1" do |ubuntuvm1|
    ubuntuvm1.vm.box = "ubuntu/groovy64"
    ubuntuvm1.vm.network "private_network", ip: "10.0.0.51"
    ubuntuvm1.vm.hostname = "ubuntuvm1"
  end
#Development Server configuration
  config.vm.define "centosvm2" do |centosvm2|
    centosvm2.vm.box = "centos/8"
    centosvm2.vm.network "private_network", ip: "10.0.0.52"
    centosvm2.vm.hostname = "centosvm2"
  end
end
