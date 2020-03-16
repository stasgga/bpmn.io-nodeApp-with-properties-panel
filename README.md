# bpmn.io-nodeApp-with-properties-panel
based [bpmn-io/bpmn-js-examples/properties-panel](https://github.com/bpmn-io/bpmn-js-examples/tree/master/properties-panel)

This example uses [bpmn-js](https://github.com/bpmn-io/bpmn-js) 
and [bpmn-js-properties-panel](https://github.com/bpmn-io/bpmn-js-properties-panel). 

It implements a BPMN 2.0 modeler that allows you to edit execution related properties via a properties panel *you can show or hide*.

## About

This example is a node-style web application that builds a user interface around the bpmn-js BPMN 2.0 modeler.

![demo application screenshot](https://raw.githubusercontent.com/bpmn-io/bpmn-js-examples/master/properties-panel/docs/screenshot.png 
"Screenshot of the modeler + properties panel example")

## Building the Example

You need a [NodeJS](http://nodejs.org) development stack with [npm](https://npmjs.org) and installed to build the project.

To install all project dependencies execute

```
npm install
```

Build the example using [browserify](http://browserify.org) via

```
npm run all
```

You may also spawn a development setup by executing

```
npm run dev
```

Both tasks generate the distribution ready client-side modeler application into the `dist` folder.

Serve the application locally or via a web server (nginx, apache, embedded).
