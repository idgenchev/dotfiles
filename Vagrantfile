# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.define "vagrant" do |vagrant|
    vagrant.vm.box = "bento/ubuntu-20.04"
    vagrant.vm.provider :virtualbox do |v|
      v.memory = 768
      v.linked_clone = true
    end

    vagrant.vm.provision "ansible_local" do |ansible|
      ansible.playbook = "playbook.yaml"
    end
  end
end
