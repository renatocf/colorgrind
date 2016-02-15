# Colorgrind
Colorgrind: a Perl wrapper for Valgrind with ANSI escape code colored output

## Installation

In order to install colorgrind, download the script and put in a directory listed in your `$PATH`. Colorgrind runs in a Perl interpreter and depends on the [Term::ANSIColor](http://perldoc.perl.org/Term/ANSIColor.html) module.

## Usage

In order to use colorgrind, just substitute `valgrind` by `colorgrind` in your shell commands.

## Contributing

In order to contribute, open a [Pull Request](https://github.com/renatocf/colorgrind/pulls). In the current stage of development, Colorgrind works for Valgrind's `memchek` output in a dark style terminal.

## License

Colorgrind is distributed with a MIT License. Check [LICENSE](https://github.com/renatocf/colorgrind/blob/master/LICENSE) for further info.
