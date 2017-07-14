ansible-apache-rpmbuild
====

Generate rpm of Apache httpd.

## Description
This program uses Vagrant to make rpms with Virtualbox and ansible.

## Requirement
* Vagrant
* Virtualbox

## Usage
    $ git clone https://github.com/futuremaze/ansible-apache-rpmbuild.git
    $ export http_proxy=http://USERNAME:PASSWORD@PROXY_HOST:PORT # It is the same with above.
    $ vagrant plugin install vagrant-proxyconf # if you need proxy server configuration to connect to the Internet.
    $ vagrant up
    $ vagrant halt
    $ cp ./rpmbuild /path/to

## Licence

[MIT](https://github.com/futuremaze/ansible-apache-rpmbuild/blob/master/LICENSE)

## Author

[futuremaze](https://github.com/futuremaze)

