# Introduction
GAMADV-XTD3 is a free, open source command line tool for Google G Suite Administrators to manage domain and user settings quickly and easily.

GAMADV-XTD3 is built with Python 3; as Python 2 support ends on 2020-01-01, this is the version of Advanced GAM that new/existing users should install.

This page provides simple instructions for downloading, installing and starting to use GAMADV-XTD3.

GAMADV-XTD3 requires G Suite for Business, Education, Non Profit, Partner or Government Edition. Google Apps Free Edition has limited API support and not all GAM commands work.

GAMADV-XTD3 is a rewrite/extension of Jay Lee's [GAM], without his efforts, this version wouldn't exist.

GAMADV-XTD3 is backwards compatible with [GAM], meaning that if your command works with regular GAM, it will also work with GAMADV-XTD3. There may be differences in output, but the syntax is compatible.

# Documentation
Basic GAM documentation is hosted in the [GitHub Wiki]. Documentation specifically for GAMADV-XTD3 is hosted in the [GitHub GAMADV-XTD3 Wiki] and in Gam*.txt files.

# Mailing List / Discussion group
The GAM mailing list / discussion group is hosted on [Google Groups].  You can join the list and interact via email, or just post from the web itself.

# Source Repository
The official GAMADV-XTD3 source repository is on [GitHub] in the master branch.

# Author
GAMADV-XTD3 is maintained by <a href="mailto:ross.scroggs@gmail.com">Ross Scroggs</a>.

# Requirements
To run all commands properly, GAMADV-XTD3 requires three things:
* An API project which identifies your install of GAMADV-XTD3 to Google and keeps track of API quotas.
* Authorization to act as your G Suite Administrator in order to perform management functions like add users, modify group settings and membership and pull domain reports.
* A special service account that is authorized to act on behalf of your users in order to modify user-specific settings and data such as Drive files, Calendars and Gmail messages and settings like signatures.

# Installation - First time GAM installation
Use these steps if you have never used any version of GAM in your domain. They will create a GAM project
and all necessary authentications.

* [Downloads]
* [Configuration]
* [Install]

# Installation - Upgrading from a GAM version other than a prior version of GAMADV-X or GAMADV-XTD or GAMADV-XTD3
Use these steps if you have used any version of GAM in your domain. They will update your GAM project
and all necessary authentications.

* [Downloads]
* [Configuration]
* [Upgrade]

# Installation - Upgrading from a prior version of GAMADV-X or GAMADV-XTD or GAMADV-XTD3
Use these steps if you already use GAMADV-X or GAMADV-XTD or GAMADV-XTD3. The updates may tell you to update your GAM project
or authentications because new features have been included.

* [Updates]
* [Downloads]

# Multiple Versions
You can install multiple versions of GAM, GAMADV-X, GAMADV-XTD and GAMADV-XTD3 in different parallel directories.

[GAM]: https://github.com/jay0lee/GAM
[GitHub Releases]: https://github.com/taers232c/GAMADV-XTD3/releases
[GitHub]: https://github.com/taers232c/GAMADV-XTD3/tree/master
[GitHub Wiki]: https://github.com/jay0lee/GAM/wiki/
[GitHub GAMADV-XTD3 Wiki]: https://github.com/taers232c/GAMADV-XTD3/wiki/
[Google Groups]: https://groups.google.com/group/google-apps-manager
[Downloads]: https://github.com/taers232c/GAMADV-XTD3/wiki/Downloads
[Configuration]: https://github.com/taers232c/GAMADV-XTD3/wiki/gam.cfg
[Install]: https://github.com/taers232c/GAMADV-XTD3/wiki/How-to-Install-Advanced-GAM
[Upgrade]: https://github.com/taers232c/GAMADV-XTD3/wiki/How-to-Upgrade-from-Standard-GAM
[Updates]: https://github.com/taers232c/GAMADV-XTD3/wiki/GAM-Updates
