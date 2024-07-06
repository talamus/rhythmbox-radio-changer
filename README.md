# Rhythmbox Internet radio channel changer

Change [Rhythmbox](https://en.wikipedia.org/wiki/Rhythmbox) Internet radio channels from the command line.

This command line program scans the `~/.local/share/rhythmbox/rhythmdb.xml` for Internet radio channels, and switches to a new one.

Bind it to a keyboard shortcuts, and change a channel in a breeze.

## Usage

```text
usage: rhythmbox-radio-changer [-h] [-r RATING] next|prev|random

Change Rhythmbox internet radio channels from the command line.

positional arguments:
  next|prev|random      what will be played next

options:
  -h, --help            show this help message and exit
  -r RATING, --rating RATING
                        minimum star rating for station to play

To get more output set the LOG_LEVEL to INFO:
LOG_LEVEL=INFO rhythmbox-radio-changer ...
```

## Dependencies

* Python 3.10 or newer
* `rhythmbox-client` must be installed

No additional libraries are used.

