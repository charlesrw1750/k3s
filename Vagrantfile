Vagrant.configure("2") do |config|
    config.vm.box = "centos/7"
    config.vm.hostname = "manager"
    config.vbguest.installer_options = { allow_kernel_upgrade: true }
    config.vm.network "private_network", ip: "192.168.1.2"
    config.vm.provider 'virtualbox' do |vb|    
        vb.memory = "6048"
    end
end
