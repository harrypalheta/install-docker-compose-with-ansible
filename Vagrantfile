Vagrant.configure(2) do |config|
    config.vm.define "focal" do |config|
      config.vm.box = "ubuntu/focal64"
      config.vm.hostname = "focal"
      config.vm.network "private_network", ip: "10.0.20.4"
    end

    # config.vm.provider "virtualbox" do |v|
    #     v.memory = 1024
    #     v.cpus = 2
    # end
end
  