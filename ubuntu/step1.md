What's new in Ubuntu 16.04

## Task

First let's see what version we got 

`cat /etc/*release`{{execute}}

If you are used to using to apt-get, then you can now just use apt:

`apt update`{{execute}}

Ubuntu 16.04 comes with both Python versions 3.5.1 and 2.7. 

`ls /usr/lib/python*`{{execute}}

let's what packages we have

`apt list`{{execute}}

we got systemd 

`apt search systemd`{{execute}}

lets see what services are running

`systemctl list-unit-files --type=service`{{execute}}

now lets change our observable

`map.set("key", "new value")`{{execute}}
