# Boilerplate for BackboneJS projects using RequireJS

This is a simple boilerplate to quickly get projects going using Backbone and RequireJS.

## What is this?

This is just a simple boilerplate to quickly get going with projects.  I got tired of recreating the same code, folder structure, etc, so I just put this up.  This is by no means all-inclusive, but I wanted to keep it as bare bones as possible for anyone to include whatever other libraries they wish.  For example, I tend to use templating libraries other than underscore.  But I don't want to be presumptive and ad any here when you may want to use a different one.  (There's plenty of opinionated-ness in the structure).

## Included libraries

RequireJS v1.0.4

jQuery v1.7.1

Underscore v1.2.4

Backbone v0.5.3 branch https://raw.github.com/jrburke/backbone/optamd3/backbone.js  
NormalizeCSS 2011-11-04

## Getting started

To start, just download the boilerplate and point your browser to the index.html file in the root folder.  If everything is working, you should see "App Initialized!" in the window.

  


The core of the app can be found in the folder src/js.  Here, you can find the folders 'models', 'collections', 'views', and 'templates' each containing a simple stub to copy for new modules.

  


The basic flow can be seen by tracing through the default initialization app.  This has three basic parts:

  


1) The main template found in src/js/templates/main.html

2) The main view found in src/js/main-view.js

3) The main application found in src/js

  


The code is pretty simple and should give you an idea how to layout your app in this boilerplate.

  


_Note: A router wasn't included by default.  Most applications require just one router meaning no need to stub.  You can just create one and insert into your app as needed_

  


Additionally, an example Todo example can be found at [http://davidgranado.com/demos/todo-example/][1]
git 
   [1]: http://davidgranado.com/demos/todo-example/
