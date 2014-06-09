# Custom Weswit template for JSDoc 3

This is a custom [jsdoc3](https://github.com/jsdoc3/jsdoc) template derived from the [default template](https://github.com/jsdoc3/jsdoc/tree/master/templates/default).

This templates adds:
* A methods summary in class/module documentation (including a list of inherited methods linking to their original documentation).
* An alphabetical index page.
* The possibility to add a logo to the documentation
* The possibility to configure a custom footer
* The possibility to import an html snippet as summary page
* The possibility to configure the title of the the index page
* Removes sources references when sources are not part of the output

We use this template to generate the documentation of our JavaScript library. You can see a live example: [Lightstreamer JavaScript client API](http://www.lightstreamer.com/docs/client_javascript_uni_api/index.html)

## Usage
Just drop the weswit-template folder under the templates folder of jsdoc and configure jsdoc to use it. Optionally you can extend your jsdoc.json conf as shown in the example_conf.json file included in this project
