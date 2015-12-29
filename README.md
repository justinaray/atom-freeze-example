# Atom-freeze-example

This Repo exists to demonstrate a freeze example in the atom text editor.

To Freeze atom:
* Open app/components/example-one/template.hbs
* Open app/components/example-two/template.hbs
* Open app/example-one/template.hbs

Atom will freeze while trying to open the file.  Originally, I thought this was
due to handlebars/mustache, but the issue persists even after that package is disabled.

This is obviously related to the sub-folders and files being named similarly but in separate directory hierarchies.

Unfortunately, the freeze makes it impossible to grab a CPU profile.

Thanks to @lee-dohm for all his help on the slack channel.



## Prerequisites

You will need the following things properly installed on your computer.

* [Git](http://git-scm.com/)
* [Node.js](http://nodejs.org/) (with NPM)
* [Bower](http://bower.io/)
* [Ember CLI](http://www.ember-cli.com/)
* [PhantomJS](http://phantomjs.org/)

## Installation

* `git clone <repository-url>` this repository
* change into the new directory
* `npm install`
* `bower install`

## Running / Development

* `ember server`
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
