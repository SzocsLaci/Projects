Vagrant.configure("2") do |config|

  config.vm.box = "codecool/ubuntu-18.04-base"
  #config.vm.provider "virtualbox"
  config.vm.network "forwarded_port", guest: 8080, host: 8080
  #config.vm.synced_folder "/home/szocslaci/Asztal/Tomcat/share", "/tmp/share"
  config.vm.provision :shell, path: "provision1.sh"
end
