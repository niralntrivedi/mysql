# mysql
Mysql Setup Chef Cookbook

Follow these steps to get the working mysql setup on vagrent machine on your OSX.

Make sure that you have chef, vagrent and virtualbox installed on your Mac.

* git clone https://github.com/niralntrivedi/mysql.git
* cd mysql/environment
* vagrant up
* git submodule add https://github.com/opscode-cookbooks/mysql.git environment/cookbooks/mysql
* vagrant plugin install vagrant-omnibus
* git submodule add https://github.com/opscode-cookbooks/yum.git environment/cookbooks/yum
* vagrant provision
