![icons8-контроль-96](https://github.com/mnd0929/api/assets/92184643/956c2169-9e51-4a0d-ae66-18a4ef69a5b1)

# API
[![Releases](https://img.shields.io/badge/All%20compiled%20versions-red)](https://github.com/mnd0929/api/releases)
[![Releases](https://img.shields.io/badge/build-ltsv-blue)](https://github.com/mnd0929/api/releases/tag/ltsv)
[![Releases](https://img.shields.io/badge/build-sv-blue)](https://github.com/mnd0929/api/releases/tag/api)
[![Discord](https://img.shields.io/badge/Discord-blue)](https://discord.gg/x7xMShAzck)

Quick Installation Script Manager (QISL). Uses the PIGET package library.

[Help](https://raw.githubusercontent.com/mnd0929/api-apps/main/help) | [PIGET](http://tgcch.byethost7.com/piget/pl.php?filter=) | feedback@xon-4de.ru | support@xon-4de.ru 

# Installation

API installation methods:
- [API Bitsadmin Installation](https://raw.githubusercontent.com/mnd0929/api-apps/main/updatecommand-bitsadmin.txt) (Requires bitsadmin)
- [API Powershell Installation](https://raw.githubusercontent.com/mnd0929/api-apps/main/updatecommand.txt) (Requires powershell)
- [API GUI Installation](https://github.com/mnd0929/API-Installer/releases)

<!> Supported platforms: ```win-x86```, ```win-x64```

<!> False positives of antiviruses are possible - the application does not have a digital signature




# Quick Install Script Library
PIGET is a public QISL (Quick Install Script Library). Users can create and install scripts, which can be quickly accessed through the API (Automatic Package Installer) console program.

# Package structure
The package must be a ZIP archive and contain the ```installer.bat``` file.
After downloading the package, the API unpacks it and runs the installer.bat command line script.
The API also passes arguments entered by the user after the package name. (```api targ 1 2 3 4 5```)

# How do I register my QISL package with PIGET? (API 4.7.3+)
- Enter the ```api -piget``` command into the console without administrator rights.
- Select "CREATE NAME PIGET PACKAGE".
- Enter the package name. (Later you will be able to run your QISL package through the ```api <package_name>``` command. The package name should not contain spaces, special characters and capital letters. A package that violates the naming rules will not be displayed on the site, but it can be executed manually by writing the name in quotes)
- If the name is available, enter the description, icon address and api command: ```api <direct_link_to_package>```. You can get a direct link to the package by uploading it to Discord, Yandex Disk, and cloud storage with this functionality. (The direct link at the end has a file extension, in our case .zip)
- Check the data you entered; after registration it will not be possible to change it. If everything is correct, confirm it with the appropriate letter. To confirm the registration of the package, enter the code from the quotes and press Enter.
