# ember.d.ts

Intellisense d.ts generator for Ember

## Use

* Copy generated YUIDoc `data.json` from the Ember repo to `docs.json`.
* `node generate.js`

## TODO

* Generate separate definition without prototype extensions
* Handle additional JSDoc properties (@param, @return)
* Define types of arrays where possible
* Review situations where multiple types are possible
* Review var-args
* JSDoc for classes and namespaces if supported
* Ignore Handlebars helpers?
* Don't hardcode docs.json path
* Declare DOM classes, e.g. DOMElement
* Declare generic Promise
* Depend on jQuery
* Figure out if we can ignore warnings about improper implementation for mixins