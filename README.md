#                                 TX


TBomb
TBomb v2.1b
A free and open-source SMS/Call bombing application

NOTES:
Due to the overuse of script, a bunch of APIs have been taken offline. It is okay if you do not receive all the messages.

Termux version from Play Store is not supported since 2019, please use the latest version from F-Droid Store!

The application requires active internet connection to contact the APIs
You would not be charged for any SMS/calls dispatched as a consequence of this script
For best performance, use single thread with considerable delay time
Always ensure that you are using the latest version of TBomb and have Python 3
This application must not be used to cause harm/discomfort/trouble to others
By using this, you agree that you cannot hold the contributors responsible for any misuse
Compatibility
Check your Python version by typing in

$ python --version
If you get the following

Python 3.8.3
or any version greater than or equal to 3.4, this script has been tested and confirmed to be supported. For obsolete versions of Python (eg 2.7), use discretion while executing the script as it has not been tested there.

Features
Over 15 integrated messaging and calling APIs included with JSON
Unlimited (with abuse protection) and super-fast bombing with multithreading
Possibility of international API support (APIs are offline)
Flexible with addition of newer APIs with the help of JSON documents
Actively supported by the developers with frequent updates and bug-fixes
Intuitive auto-update feature and notification fetch feature included
Recently made free and open-source for community contributions
Modular codebase and snippets can be easily embedded in other program
Usage:
Install by PIP (Recommended)
Before continuing make sure following requirements are satisfied:

Python version greater than or equal to 3.4 is installed
pip is installed for Python 3
Install tbomb package by running:

pip3 install tbomb
Run TBomb by just typing:

tbomb
Install from GIT
NOTE
Git installation methods are not universal and are likely to differ between distributions so installing Git as per the given instructions below may not work. Please check out how to install Git for your Linux distribution here. Commands below provide instructions for Debian-based systems.

Running TBomb.sh as sudo miscofigures files ownership. It is recommended not to run it as sudo

Run these commands to clone and run TBomb.

For Termux
To use the bomber type the following commands in Termux:

pkg install git -y 
pkg install python -y 
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
./TBomb.sh
For iSH
To use the application, type in the following commands in iSH.

apk add git
apk add python3
apk add py3-pip
apk add ruby
gem install toilet
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
pip3 install -r requirements.txt
chmod +x TBomb.sh
./TBomb.sh
For Debian-based GNU/Linux distributions
To use the application, type in the following commands in GNU/Linux terminal.

sudo apt install git
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
bash TBomb.sh
For MacOS
To use the application, type in the following commands in MacOS terminal:

Install via Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install dependencies:
brew install git
brew install python3
sudo easy_install pip
sudo pip install --upgrade pip
git clone https://github.com/TheSpeedX/TBomb.git
cd TBomb
bash TBomb.sh
