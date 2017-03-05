# UCSF Linux Toolbox

The UCSF Linux Toolbox is a collection of Linux tools that are useful for Linux users working at the University of California San Francisco (UCSF):

* [`ucsf vpn`](docs/ucsf-vpn.md): Connect and Disconnect to the UCSF VPN



## Usage
```sh
$ ucsf --help
UCSF Command Line Tools

Usage:
 ucsf <tool> ...

Installed tools:
 vpn       Connect and Disconnect to the UCSF VPN

Example:
 ucsf vpn --help

Version: 1.0.0
Copyright: Henrik Bengtsson (2016-2017)
License: GPL (>= 2.1) [https://www.gnu.org/licenses/gpl.html]
```


## Installation

```sh
$ mkdir ~/bin
$ cd bin
$ wget https://raw.githubusercontent.com/UCSF-tools/ucsf-tools/master/bin/ucsf
$ wget https://raw.githubusercontent.com/UCSF-tools/ucsf-tools/master/bin/ucsf-v
pn
$ chmod ugo+x ucsf ucsf-vpn
$ ~/bin/ucsf --version
1.0.0
$ ~/bin/ucsf --tools
vpn
```
