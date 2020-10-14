Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.network "forwarded_port", guest: 8088, host: 8000
# command ip dinamico ---> config.vm.network "private_network", type: "dhcp"
# command ip estatico ---> config.vm.network "private_network", ip: "192.168.50.4"
end
