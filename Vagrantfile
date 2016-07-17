Vagrant.configure(2) do |config|


    config.vm.box = "kaorimatz/ubuntu-16.04-amd64"
    config.ssh.insert_key = false
  
    config.vm.provider "virtualbox" do |v|
      v.name = "map"
      v.memory = 4000
      v.cpus = 4
    end

    config.vm.hostname = "map"
    config.vm.network :private_network, ip: "192.168.55.4"

    
    # config.vm.provision "ansible" do |ansible| 
    #     ansible.playbook = "provision/playbook.yml"
    # end
end