Vagrant.configure(2) do |config|

  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "rember.be"
  config.vm.network "forwarded_port", guest: 80, host:1234
  config.vm.provision "shell", path: "provisioning_nginx.sh"
  config.vm.provision "shell", path: "provision_php.sh"
end