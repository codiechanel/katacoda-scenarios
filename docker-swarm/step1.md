This is your first step.

## Task

First let's install dependencies

The dashboard is running on Port 9000 and can be accessed via [this link](https://[[HOST_SUBDOMAIN]]-9000-[[KATACODA_HOST]].environments.katacoda.com)

6) Visit the newly deployed container on [port 80](https://[[HOST_SUBDOMAIN]]-80-[[KATACODA_HOST]].environments.katacoda.com)

`npm i mobx`{{execute}}

lets go to node shell and start coding

`node`{{execute}}

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
