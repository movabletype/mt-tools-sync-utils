# mt-tools-sync-utils
This utility program allows you to show list of content sync settings, show setting details, and connection test.

AUTHOR: Six Apart

COPYRIGHT: 2019, Six Apart


## Installation
Move the sync-utils program into the MT tools directory.
Should look like this when installed:

$MT_HOME/
    tools/

## Usage
perl -Ilib -Iextlib tools/sync-utils

    -a, --list-all     Prints list of server sync settings.
    -l, --list [<ID>]  Prints list of server sync settings Specify the ID of blog.
    -d, --detail <ID>  Prints detail of sync settings. Specify the ID of sync setting.
    -t, --test <ID>    Prints result of connection test. Specify the ID of sync setting.
    -v, --verbose      Prints detail of connection. (only for -t)
    -h, --help         this.


## Support
This program is not an official Six Apart release, and as such support for this program is not available.
