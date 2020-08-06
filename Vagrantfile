# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|
  config.ssh.insert_key = false
  config.vm.define  "base" do | vmachine |
  vmachine.vm.box = "centos/8"
  vmachine.ssh.insert_key = false
  #cmd = "yum install -y kernel-devel-uname -r--enablerepo=C*-base --enablerepo=C*-updates"
  config.vm.synced_folder ".", "/vagrant", type: "virtualbox"
    vmachine.vm.hostname = "gold"
    vmachine.vm.provider "virtualbox" do | virtualbox |
      virtualbox.memory = "1024"
      virtualbox.cpus = 1
      virtualbox.name = "gold"
  end
end
end

Vagrant.configure("2") do |config|
  config.ssh.insert_key = false
  config.vm.define  "docker" do | vmachine |
  vmachine.vm.box = "gold"
  vmachine.ssh.insert_key = false
  vmachine.vm.network "private_network", ip: "192.168.100.190"
  #cmd = "yum install -y kernel-devel-uname -r--enablerepo=C*-base --enablerepo=C*-updates"
  config.vm.synced_folder ".", "/vagrant", type: "virtualbox"
    vmachine.vm.hostname = "docker"
    vmachine.vm.provider "virtualbox" do | virtualbox |
      virtualbox.memory = "1024"
      virtualbox.cpus = 1
      virtualbox.name = "docker"
  end
end
end

#Vagrant.configure("2") do |config|
  #config.ssh.insert_key = false
  #config.vm.define  "dockertest" do | vmachine |
  #vmachine.vm.box = "gold"
  #vmachine.ssh.insert_key = false
  #vmachine.vm.network "private_network", ip: "192.168.100.191"
  ##cmd = "yum install -y kernel-devel-uname -r--enablerepo=C*-base --enablerepo=C*-updates"
  #config.vm.synced_folder ".", "/vagrant", type: "virtualbox"
    #vmachine.vm.hostname = "dockertest"
    #vmachine.vm.provider "virtualbox" do | virtualbox |
      #virtualbox.memory = "1024"
      #virtualbox.cpus = 1
      #virtualbox.name = "dockertest"
  #end
#end
#end

Vagrant.configure("2") do |config|
  config.ssh.insert_key = false
  config.vm.define  "docker1" do | vmachine |
  vmachine.vm.box = "gold"
  vmachine.ssh.insert_key = false
  vmachine.vm.network "private_network", ip: "192.168.100.192"
  #cmd = "yum install -y kernel-devel-uname -r--enablerepo=C*-base --enablerepo=C*-updates"
  config.vm.synced_folder ".", "/vagrant", type: "virtualbox"
    vmachine.vm.hostname = "docker1"
    vmachine.vm.provider "virtualbox" do | virtualbox |
      virtualbox.memory = "1024"
      virtualbox.cpus = 1
      virtualbox.name = "docker1"
  end
end
end

Vagrant.configure("2") do |config|
  config.ssh.insert_key = false
  config.vm.define  "docker2" do | vmachine |
  vmachine.vm.box = "gold"
  vmachine.ssh.insert_key = false
  vmachine.vm.network "private_network", ip: "192.168.100.193"
  #cmd = "yum install -y kernel-devel-uname -r--enablerepo=C*-base --enablerepo=C*-updates"
  config.vm.synced_folder ".", "/vagrant", type: "virtualbox"
    vmachine.vm.hostname = "docker2"
    vmachine.vm.provider "virtualbox" do | virtualbox |
      virtualbox.memory = "1024"
      virtualbox.cpus = 1
      virtualbox.name = "docker2"
  end
end
end