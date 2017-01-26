# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "https://github.com/tommy-muehle/puppet-vagrant-boxes/releases/download/1.0.0/centos-6.6-x86_64.box"

  # Proxy settings
  if Vagrant.has_plugin?("vagrant-proxyconf") &&
     (ENV['http_proxy'] || ENV['https_proxy'])
    config.proxy.http = ENV['http_proxy']
    config.proxy.https = ENV['https_proxy']
    config.proxy.no_proxy = "localhost,127.0.0.1"
  end
end
