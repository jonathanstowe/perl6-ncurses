# NCurses

[![Build Status](https://travis-ci.org/azawawi/perl6-ncurses.svg?branch=master)](https://travis-ci.org/azawawi/perl6-ncurses)

NCurses provides a Perl 6 interface to libncurses.

## Installation

* Since NCurses uses libncurses, libncurses.so must be found in /usr/lib.
To install libncurses on Debian for example, please use the following command:

```
	sudo apt-get install libncurses5
```

* Using panda (a module management tool bundled with Rakudo Star):

```
    panda update && panda install NCurses
```

## Testing

To run tests:

```
    prove -e perl6
```

## Author

Ahmad M. Zawawi, azawawi on #perl6, https://github.com/azawawi/

## License

Artistic License 2.0
