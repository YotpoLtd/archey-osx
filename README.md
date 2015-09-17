#Archey for OS X
An archey script for OS X.

```
                                                         User: yotpo
                                                         Hostname: user.yotpo.com
                                                         Distro: OS X 10.10.4
   ##    ##  #######  ######## ########   #######        Kernel: Darwin
    ##  ##  ##     ##    ##    ##     ## ##     ##       Uptime: 15:29  up 15 days,  6:13, 1 user, load averages: 1.83 1.99 2.04
     ####   ##     ##    ##    ##     ## ##     ##       Shell: /bin/zsh
      ##    ##     ##    ##    ########  ##     ##       Terminal: xterm iTerm.app
      ##    ##     ##    ##    ##        ##     ##       Packages: 63
      ##    ##     ##    ##    ##        ##     ##       CPU: Intel Core i5-4258U CPU @ 7.40GHz
      ##     #######     ##    ##         #######        Memory: 8 GB
                                                         Disk: 55%
                                                         IP Address: 1.2.3.4

```

##Table Of Contents
* [Download](#download)
* [Installation](#installation)
* [Options](#options)
* [Credits](#credits)
* [License](#license)

##Download
The latest stable release is [1.4](https://github.com/obihann/archey-osx/archive/1.4.tar.gz).

##Installation
To get started you will need [homebrew](http://brew.sh/) to manage packages such as Python, figlet, and cowsay. To install please run the following command:

```
brew tap yotpoLtd/yotpo
cd /usr/local/Library/Taps/yotpoltd/homebrew-yotpo
git remote set-url origin git@github.com:yotpoLtd/homebrew-yotpo.git
brew install yotpo-archey
```

##Options
------------
* -b,  --nocolor : Use black & white logo
* -c,  --color   : Force using a color Logo
* -m,  --macports : Use MacPorts instead of Homebrew to display package count
* -h,  --help : Show help


##Credits
------
* [djmelik](https://github.com/djmelik/archey) - Archey
* [joshfinnie](https://github.com/joshfinnie/archey-osx) - A great OSX Python port of Archey
* [Gary00](https://github.com/Gary00/archey-osx) - A fork of joshfinnie's Archey port, and the base of this script.
* [rdlugosz](https://github.com/rdlugosz) - Fixing a math error with memory caculations.
* [docwhat](https://github.com/docwhat) - Shell expertise and cleanups.

##License

This tool is protected by the [GNU General Public License v2](http://www.gnu.org/licenses/gpl-2.0.html).

Copyright [Jeffrey Hann](http://jeffreyhann.ca/) 2013,2014
