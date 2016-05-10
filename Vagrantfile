Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/trusty64"
  config.vm.hostname = "rember.be"
  config.vm.network "forwarded_port", guest: 80, host: 6666
end
