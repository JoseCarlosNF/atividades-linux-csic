# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "debin/buster64"

  config.vm.define :VM1 do |vm1|
    vm1.vm.network :private_network, :ip => "192.168.10.2"
  end

  config.vm.define :VM2 do |vm2|
    vm2.vm.network :private_network, :ip => "192.168.10.3"
  end

  config.vm.define :VM3 do |vm3|
    vm3.vm.network :private_network, :ip => "192.168.10.4"
  end

end
