<p align="center">
  <img src="media/banner.png" />
</p>
# MPSBrute
[![GitHub Build](https://img.shields.io/scrutinizer/build/g/filp/whoops.svg)](README.md)
[![GitHub License](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)
[![GitHub Version](https://img.shields.io/badge/version-1.0.0-orange.svg)](README.md)
[![GitHub Issues](https://img.shields.io/badge/issues-0-yellow.svg)](https://github.com/AaronVigal/MPSBrute/issues)
[![GitHub Completion](https://img.shields.io/badge/completion-0 percent-red.svg)](README.md)


An application to brute force all known Millard Public Schools logins to maximize the time it takes to crack each password

Table of Contents
==================

1. [Main Features] (#main-features)
2. [Dependencies] (#dependencies)
3. [Installation] (#installation)
  * [Automatic Installation] (#automatic-installation)
  * [Manual Installation] (#manual-installation)
4. [Usage] (#usage)
  * [Command Line Arguments] (#command-line-argumets)
  * [Terminal Interface] (#terminal-interface)
  * [GUI Interface] (#gui-interface)
4. [Future Integrations] (#future-integrations)
5. [License] (README.md)

Main Features
=============

The concept behind this program is hitting the maximum attemps per minute as your hardware allows, to thread the application, and to hit multiple websites at one time. This will ensure the highest attemps per minute and ensure the smallest ammount of time per password.

Our main attack features a highly efficient brute force method running 64 threads per playform across 10 vulnerable websites boasting a massive 1790 passwords per minute.

Dependencies
============

If you are using this application on Kali Linux as reccomended, this shouldn't be an issue for you. However, if you are installing this from the source, you could run into touble if you don't have these installed.

Installation
============

If you are on Kali Linux (reccomended), the installation is simple to do with the given <code>.deb</code> file and using the automatic installation. However, if you prefer to install it from source, there is an option for that also.


Automatic Installation
----------------------

Manual Installation
-------------------


Usage
=====

Command Line Arguments
----------------------
|     Argument    | Function Information                                                                                               |
|:---------------:|--------------------------------------------------------------------------------------------------------------------|
| -h // --help    | Displays the help manual on how to use the tool to it's full capabilities.                                         |
| -v // --verbose | Turns on verbose mode for extended information on what the application is doing.                                   |
| -i // --info    | Displays information about the tool like System Info, Version Number, Developer Information.                       |
| -u // --update  | Checks the version number against the newest version on our GitHub repository and automatically updates if needed. |

GUI Interface
-------------
