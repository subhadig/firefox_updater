# Firefox updater

Updater cum installer script for Firefox for Linux.
This is useful if your distribution does not have the latest Firefox package
available in the repo.

# Steps

1. Clone this repository and run `firefox-updater.sh` from a user with admin
rights or use root.
It downloads the latest Firefox tar from the official source, unpackages and
places in `/opt` and creates the `firefox-latest` link under `/usr/bin`.

2. At this point, you can start the Firefox browser by executing the
`firefox-latest` command.
But presumably you would also want to create a desktop launcher to be able to
easily access Firefox.
I use [MenuLibre](https://bluesabre.org/menulibre/) for easily creating
launchers but you can create them with any other compatible tool or by
manually creating the launcher file.
