Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/xenial64"

  config.vm.provision "shell", path:"provision.sh"

  config.vm.provision "ansible_local" do |ansible|
    ansible.provisioning_path = "/vagrant"
    ansible.verbose = "vvv"
    ansible.playbook = "playbook.yaml"
  end
end
