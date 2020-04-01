# CoH-Mac-Setup
Setup for City of Heroes on a Mac

1. Open Terminal (Finder > Applications > Utilities > Terminal)
2. Install Brew - https://brew.sh/ - allows you to easily install other applications/files
    1. Run: ```/bin/bash -c "$(curl -fsSL     https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"```
3. Install xquartz if you don’t have it - allows you to run windows software on your Mac in a separate window
    1. Run: ```brew cask install xquartz```
4. Install wine - this allows you to run .exe (windows) files on Mac needed to retain City of Heroes data.  Original wine was deprecated with Mac updates, so we're installing a branched version
    1. Run: ```brew cask install wine-stable```
5. Close Terminal
6. Install Island Rum (Do Not Proceed Here Until Wine is Installed) - This is the City of Heroes application
    1. http://telstar.eekstudio.com/islandrum-mac.zip
7. Extract and move to Applications folder to find more easily
8. Run Island Rum - this takes a while (make sure brew and wine were installed before)
9. Once Island Rum completes it's download of all the City of Hereos files, close and restart your computer
    1. Most people experience issues trying to start without restarting your computer.  You just downloaded a bunch of stuff, give your PC a little rest and you should be able to start up CoH again
10. Create your accounts
    1. Forum account - https://forums.homecomingservers.com/register/
    2. Game account (need both) - https://forums.homecomingservers.com/gameaccount/
        1. This is your login to City of Heroes
11. Startup Rum Island and you should be good to go!
