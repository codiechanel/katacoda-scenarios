This is your first step.

## Task

This is an _example_ of creating a scenario and running a **command**

`echo 'Hello World'`{{execute}}

First let's install dependencies

`npm i mobx`{{execute}}

lets go to node shell and start coding

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
