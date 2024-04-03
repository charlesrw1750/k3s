Vagrant.configure("2") do |config|
    config.vm.box = "centos/7"
    config.vm.hostname = "manager"
    config.vbguest.installer_options = { allow_kernel_upgrade: true }
    
    config.vm.provider 'virtualbox' do |vb|    
        vb.memory = "2048"
    end
end
