Vagrant.configure(2) do |config|
  config.vm.define "machine" do |nginx|
    machine.vm.box = "ubuntu/focal64"
    machine.vm.hostname = "machine"
    machine.vm.network "private_network", ip: "192.168.70.2"
    machine.vm.provider "virtualbox" do |v|
      v.name = "machine"
      v.memory = 4096
      v.cpus = 4
    end
  end
end


