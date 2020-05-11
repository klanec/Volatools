The zipped profile in this directory is ready to use and tested with the 
volatility pre-installed in kali linux (as of kali 2020.1) and a 1GB mem dump sample 
acquired from a totally separate identical machine set up by someone else.

Simply copy the zip as is to the volatility/plugins/overlays/linux folder and find it with

`volatility --info | grep profile`

===================

TO build your own CentOS 7.7.1908 profile for kernel 3.10.0, make sure to install
the kernel-devel rpm package in this same directory in CentOS 7.7 with `rpm -i` instead
of installing with `yum install` as that will not give you the deprecated package
