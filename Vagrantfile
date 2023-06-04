Vagrant.configure("2") do |config|
    config.vm.hostname = "ubuntu"
    config.vm.box = "ubuntu/jammy64"

    # Definir RAM e CPU
    config.vm.provider "virtualbox" do |v|
        v.memory = 1024
        v.cpus = 1
    end

    # Network
    config.vm.network "forwarded_port", guest: 80, host: 8080
    config.vm.network "public_network", ip: "192.168.15.100", bridge: "wlx000f006478a5"

end
