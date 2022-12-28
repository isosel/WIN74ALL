# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  # Box published 8 years ago
  config.vm.box = "ferventcoder/win7pro-x64-nocm-lite"

  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.network "public_network"

  config.vm.provider "virtualbox" do |vb|
    vb.memory = "4096"
    vb.cpus = 2
  end
end
