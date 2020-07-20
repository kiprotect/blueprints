# Welcome To KIProtect Blueprints

This is a repository of open, freely usable privacy & security blueprints
for KIProtect. A blueprint is a configuration file (or a collection of files)
that specifies how KIProtect should transform or analyze data for a given
use case. Blueprints enable you to quickly implement proven solutions to
common privacy and security challenges, e.g. for pseudonymization or
anonymization.

## Installing

The easiest way to use these blueprints is via the KIProtect command line
utility (CLI), which you can find
[https://github.com/kiprotect/kiprotect](here). Once you have it installed
you can download and install the blueprints in this repository using a single
command:

    kiprotect blueprints download

Then you can simply run them with the CLI tool. For example, to run the
data-types example from the pseudonymization blueprints, simply execute

    kiprotect run pseudonymization/examples/data-types/pseudonymize

If you want to learn more about all this, please check out our
[documentation](https://kiprotect.com/docs).

## License

All blueprints in this repository are licensed under a Creative Commons Zero
(CC0) license, which basically means you can freely use them in whichevery way
you like. Have a look at the [license text](LICENSE) to know the details.

## Contributing

Please feel free to contribute useful blueprints! To do that, just open
a pull-request and we will check it out right away.

## Questions, Issues?

If you have issues or suggestions, simple open an [issue](issues) in the
issue tracker. Or you can [write us an e-mail](mailto:blueprints@kiprotect.com).
