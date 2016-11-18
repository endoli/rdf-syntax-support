# rdf-syntax-support

This repository stores source files, build infrastructure,
and tests for syntax definitions for various formats used
for RDF data.

These definitions are used to generate files that are accepted
by:

* [Visual Studio Code](https://code.visualstudio.com/)
* [Atom](https://atom.io/)
* [Sublime Text](http://www.sublimetext.com/)
* [Textmate](https://macromates.com/)

## Building

First, install ``syntaxdev`` and any other required packages
by running:

    npm install .

Then to generate the syntax definitions:

    npm run build

Or to run the tests:

    npm test

## Contributing

Many things are still missing and there's a lot to do! Feel
free to dig in!

* Add your name to the `CONTRIBUTORS.rst` file.
* Make sure you add tests for your changes.
* Submit a clean pull request (no merge commits, no extra
  commits, and keep changes restricted to the purpose of
  the commit). Do ask for help if needed at this stage.

## Useful Reading

* [Syntax definitions](http://docs.sublimetext.info/en/latest/extensibility/syntaxdefs.html) from Sublime Text Unofficial Documentation
* [Scope naming conventions](https://manual.macromates.com/en/language_grammars#naming_convention)
