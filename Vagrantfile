Vagrant.configure(2) do |config|
  config.vm.box = "ubuntu/bionic64"
  config.vm.hostname = "ci-server"
  config.vm.network "forwarded_port", guest: 8080, host: 8080
end
