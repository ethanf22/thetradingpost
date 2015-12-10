# The Trading Post Git and Server Info

## Git Repository Set-Up
1. Open PhpStorm and create a new project named *thetradingpost*.
2. Once the project has loaded, open the terminal (Option + fn + F12) and enter `git init`
3. Click VCS from the menu bar and select Enable Version Control Integration. Select git from the drop down list and click OK.
4. In the terminal type: `git remote add origin ssh://username@server-ip/var/repos/thetradingpost.git`
5. Then enter: `git pull origin master`
6. Enter your password

## To Connect to the Server
1. Open the Terminal
2. Type: `ssh username@server-ip`
3. Enter password

## To Push to Github from the Server
1. Once on the server, type: `cd /var/repos/thetradingpost.git`
2. Enter: `git push github master`
