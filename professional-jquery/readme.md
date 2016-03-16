# Kendo UI Professional jQuery Boilerplate

A Kendo UI Professional jQuery Boilerplate to get you started.

### Prerequisities

Install or Update [Node.js/npm](https://nodejs.org/)

Once you have Node.js/npm working open a terminal and install [Bower](http://bower.io/) globally by running:

```
$ npm install bower -g
```

### Installing

Git Clone this [repository](https://github.com/kendo-labs/kendo-ui-boilerplates).

```
$ git clone git@github.com:kendo-labs/kendo-ui-boilerplates.git
```

or

```
$ git clone https://github.com/kendo-labs/kendo-ui-boilerplates.git
```

Or, download a [ZIP](https://github.com/kendo-labs/kendo-ui-boilerplates/archive/master.zip) of this [repository](https://github.com/kendo-labs/kendo-ui-boilerplates).

Discard all other boilerplates except the one you want to use in the directory you cloned or downloaded.

Open the boilerplate directory you want to use in your terminal.

Run the following terminal commands:

```
$ npm install
```

Then run (You'll be asked for your Telerik username and password credentials):

```
$ bower install
```

Note: In order to avoid retyping your credentials, you may cache them. The easiest way to do that is to store them as plain text in a [.netrc file](http://www.mavetju.org/unix/netrc.php). See the [documentation for more details](http://docs.telerik.com/kendo-ui/intro/installation/bower-install#kendo-ui-professional).

This will install the required [npm](https://www.npmjs.com/) and [Bower](http://bower.io/) packages.

### Running

Open a terminal from the boilerplate directory (i.e. core-jquery).

Run the following [npm scripts](https://docs.npmjs.com/misc/scripts) commands:

```
$ npm run dev-server
```

This will open the `index.html` page at localhost:4000 in your default browser using [browsersync](https://www.browsersync.io/). Browsersync has been setup to reload after any changes to any `.html`, `.css`, or `.js `files in the `dev-server` directory.

## License

This project has been released under the [Apache License, version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html)