VAGRANTFILE_API_VERSION = "2"

path = "#{File.dirname(__FILE__)}"

require 'yaml'
require path + '/scripts/homestead.rb'

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  Homestead.configure(config, YAML::load(File.read(path + '/Homestead.yaml')))


  # ADDED to configure etc/hosts file so IP is mapped to dev.prapagar.com
  
  # Used for Vagrant HostsUpdater
  config.vm.network :private_network, ip: "100.100.10.10"
  config.vm.hostname = "mission.lela.mil"

  # Set VM Name
  config.vm.provider :virtualbox do |v|
    v.customize ["modifyvm", :id, "--name", "LELA"]
  end

  # END added


end
