# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.box_check_update = false
  config.vm.hostname = "srvgitlab"
  config.vm.network "private_network", ip: "192.168.56.101"

  config.vm.provider "virtualbox" do |vb|
    vb.gui = false
    vb.name = "gitlab"
    vb.memory = "4096"
    vb.cpus = "2"
  end
end
