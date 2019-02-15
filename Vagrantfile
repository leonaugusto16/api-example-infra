Vagrant.configure("2") do |config|
  config.vm.provider "virtualbox" do |v|
    v.name = "teste_api"
    v.memory = 1024
    v.cpus = 1
  end
  config.vm.box = "centos/7"
  config.vm.network "private_network", ip: "192.168.0.4"
end
