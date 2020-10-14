Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.network "forwarded_port", guest: 8088, host: 8000
  config.vm.network "public_network"
end
