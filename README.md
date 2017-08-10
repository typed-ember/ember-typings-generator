# Ember Typings Generator
For use with [typed-ember](https://github.com/wagenet/typed-ember.git).

## LICENSE
MIT

## Usage
```sh
ember-typings-generator INPUT [OUTPUT=index.d.ts]
```

## Contributing
```sh
yarn
yarn run update -- --branch=TAG  # e.g. --branch=2.14.1
yarn run build
```
Where TAG is a tag from https://github.com/components/ember/tags

## To Do

* Properly handle prototype extensions
* Define types of arrays where possible
* Make Ember.Handlebars accessible
* Class constructors?
* See if we can further improve methods with multiple signatures
* Better handling of undeclared constants
* Consider pre-processing the docs.json so we can move hacks out of main generator code
* Basic generation tests
