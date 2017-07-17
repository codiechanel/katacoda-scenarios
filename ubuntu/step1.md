This is your first step.

## Task

First let's see what version we got 

`cat /etc/*release`{{execute}}

If you are used to using to `apt-get`, then you can now just use `apt`:

`apt update`{{execute}}

import mobx

`var mobx = require('mobx')`{{execute}}

set our observabale

`var { observable, autorun } = mobx`{{execute}}

create an observable variable

`const map = observable.map({ key: "initial value" })`{{execute}}

autorun gets invoked whenever our observable changes

`var disposer = autorun(() => {
  console.log("Invoked:", map.get("key"));
})`{{execute}}

now lets change our observable

`map.set("key", "new value")`{{execute}}
