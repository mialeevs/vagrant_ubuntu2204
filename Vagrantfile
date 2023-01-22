# Custom vagrant machine for devops - Built on Ubuntu 22.04
Vagrant.configure("2") do |config|
  config.vm.define "udevops" do |devbox|
    devbox.vm.box = "mialeevs/ubuntu2204"
    devbox.vm.box_version = "1.0.0"
    devbox.vm.hostname = "usrvp"
    devbox.vm.provider "virtualbox" do |vb|
      vb.memory = 4096
      vb.cpus = 2
    end
  end
end
