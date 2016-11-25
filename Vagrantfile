# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/atomic-host"
  config.vm.provision :shell, 
  path: "build.sh",
  keep_color: true
  config.vm.network :forwarded_port, host: 9999, guest: 80
  config.vm.define 'vagrant-centos-atomichost' do |t|
  end
end
