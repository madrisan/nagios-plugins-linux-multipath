nagios-plugins-linux-multipath
==============================

## check_multipath

This Nagios plugin checks the multipath status.

Usage

	check_multipath
	check_multipath --help
	check_multipath --version

Options 

	-h, --help                display this help and exit
	-v, --version             output version information and exit

Examples

	check_multipath

## Source code

The source code can be also found at
https://sites.google.com/site/davidemadrisan/opensource


## Installation

This package uses GNU autotools for configuration and installation.

If you have cloned the git repository then you will need to run `autogen.sh`
to generate the required files.

Run `./configure --help` to see a list of available install options.
The plugin will be installed by default into `LIBEXECDIR`.

It is highly likely that you will want to customise this location to suit your
needs, i.e.:

	./configure --libexecdir=/usr/lib/nagios/plugins

After `./configure` has completed successfully run `make install` and you're
done!


## Supported Platforms

This package is written in plain C, making as few assumptions as possible, and
sticking closely to ANSI C/POSIX.

This is a list of platforms this nagios plugin is known to compile and run on

* RedHat Enterprise Linux 5

## Bugs

If you find a bug please create an issue in the project bug tracker at
https://github.com/madrisan/nagios-plugins-linux-multipath/issues
