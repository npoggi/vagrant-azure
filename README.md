###An example of a working Vagrant + Azure provider deployment to clone/fork and experiment.

####Instructions:

##### 1.) Add the box with
vagrant box add azure https://github.com/msopentech/vagrant-azure/raw/master/dummy.box

##### 2.) Then just
**vagrant up** in the folder (azure is the default)


Runned into a couple of problems while following the instructions from both:
https://github.com/MSOpenTech/vagrant-azure/
http://blogs.msdn.com/b/tconte/archive/2014/06/19/building-your-ubuntu-php-development-box-on-azure-using-vagrant.aspx

Mainly a problem with lower case numbers:
https://github.com/MSOpenTech/azure-sdk-for-ruby/issues/2

And instructions saying you don't need to specify the cloud service name
