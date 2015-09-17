roland.codes
=====================

[![Dev Dependency Status](https://david-dm.org/Rowno/roland.codes/dev-status.svg)](https://david-dm.org/Rowno/roland.codes#info=devDependencies)
[![Dependency Status](https://david-dm.org/Rowno/roland.codes/status.svg)](https://david-dm.org/Rowno/roland.codes#info=dependencies)

This is the source code of my personal website/blog, which is a static website generated using [Metalsmith][].


Build
-----

### Setup ###

 * Install [Node.js][] v4
 * Install Gulp: `npm install -g gulp`
 * Install dependencies: `npm install`

### Tasks ###

Available build tasks:

 * `gulp` - build the website, start a server and watch for changes (implicit --watch flag).
 * `gulp build` - build the website.
 * `gulp server` - build the website and start a server.
 * `gulp alex` - run [Alex](http://alexjs.com/) over all the content.
 * `gulp lint` - run [ESLint](http://eslint.org/) over all the Javascript.

#### Flags ####

The following command line flags can also be added to tasks:

 * `--prod` - production build (minified).
 * `--watch` - watch for changes.


License
-------

Copyright © 2013 Roland Warmerdam.


[metalsmith]: http://www.metalsmith.io/
[node.js]: http://nodejs.org/
