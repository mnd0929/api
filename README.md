# API
# Automatic Package Installer

Uses the PIGET package library to look up the command: http://tgcch.byethost7.com/piget/pl.php?filter=

API GUI Installation: https://github.com/mnd0929/API-Installer/releases/tag/api-installer

API Console Installation: https://raw.githubusercontent.com/mnd0929/api-apps/main/updatecommand.txt (Elevation required)

API help: https://raw.githubusercontent.com/mnd0929/api-apps/main/help

# Package structure
The package must be a ZIP archive and contain the installer.bat file.
After downloading the package, the API unpacks it and runs the installer.bat command line script.
The API also passes arguments entered by the user after the package name. (api targ 1 2 3 4 5)

# How do I register my QISL package with PIGET? (API 4.7.3+)
1. Enter the api -piget command into the console without administrator rights.
2. Select "CREATE NAME PIGET PACKAGE".
3. Enter the package name. (Later you will be able to run your QISL package through the api <package_name> command. The package name should not contain spaces, special characters and capital letters. A package that violates the naming rules will not be displayed on the site, but it can be executed manually by writing the name in quotes)
4. If the name is available, enter the description, icon address and api command <direct_link_to_package>. You can get a direct link to the package by uploading it to Discord, Yandex Disk, and cloud storage with this functionality. (The direct link at the end has a file extension, in our case .zip)
5. Check the data you entered; after registration it will not be possible to change it. If everything is correct, confirm it with the appropriate letter. To confirm the registration of the package, enter the code from the quotes and press Enter.
