Vagrant.configure("2") do |config|

  # servidor 1
  config.vm.define "server1" do |server1|
    server1.vm.box = "ubuntu/bionic64"
    server1.vm.hostname = "server1"
    server1.vm.network "private_network", ip: "192.168.56.3"
    server1.vm.provider "virtualbox" do |vb|
      vb.memory = "256"
      vb.cpus = 1
    end
  end

 # servidor 2
  config.vm.define "server2" do |server2|
    server2.vm.box = "ubuntu/bionic64"
    server2.vm.hostname = "server2"
    server2.vm.network "private_network", ip: "192.168.56.4"
    server2.vm.provider "virtualbox" do |vb|
      vb.memory = "256"
      vb.cpus = 1
    end
  end

 # servidor 3
  config.vm.define "server3" do |server3|
    server3.vm.box = "ubuntu/bionic64"
    server3.vm.hostname = "server3"
    server3.vm.network "private_network", ip: "192.168.56.5"
    server3.vm.provider "virtualbox" do |vb|
      vb.memory = "256"
      vb.cpus = 1
    end
  end

end

