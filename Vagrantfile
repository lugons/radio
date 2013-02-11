# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant::Config.run do |config|
  config.vm.box = "squeeze"
  config.vm.network :bridged
  config.vm.forward_port 80, 8080
  config.vm.provision :puppet
end
