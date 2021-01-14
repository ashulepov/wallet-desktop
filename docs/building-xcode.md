## Build instructions for Xcode 12

### Prepare folder

Choose a folder for the future build, for example **/Users/user/Projects**. It will be named ***BuildPath*** in the rest of this document. All commands will be launched from Terminal.

### Clone source code and prepare libraries

Go to ***BuildPath*** and run

    bash <(wget -qO- wget https://raw.githubusercontent.com/ashulepov/wallet-desktop/master/install/install_mac.sh)
 
### Building the project

Launch Xcode, open ***BuildPath*/wallet-desktop/out/Wallet.xcodeproj** and build for Debug / Release.
