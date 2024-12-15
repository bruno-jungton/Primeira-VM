Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.box_version = "20191107.0.0"
  config.vm.network "forwarded_port", guest: 80, host: 8090
  config.vm.network "public_network", ip: "192.168.18.55"

  config.vm.provider "virtualbox" do |vb| 
    vb.name = "VM_01" 
    vb.memory = "1024" 
    vb.cpus = 1
  end
end