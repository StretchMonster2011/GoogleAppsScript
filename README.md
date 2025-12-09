# GoogleAppsScript
A script to add Google Chrome Apps to the local Mac

This script is designed to give Mac admins the ability to add Chrome apps to ~/Applications/Chrome Apps for users.

It is designed to run as a post install script, and I used Composer to build the package.

After you install the app on your local machine, move it to /private/tmp/ and use that to build the package.

At the end, the script calls a policy to install the icon on the Users's Dock.  I used DockUtil by KCrawford to accomplish that
