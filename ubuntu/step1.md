This is your first step.

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

autorun gets invoked whenever our observable changes

`var disposer = autorun(() => {
  console.log("Invoked:", map.get("key"));
})`{{execute}}

now lets change our observable

`map.set("key", "new value")`{{execute}}
