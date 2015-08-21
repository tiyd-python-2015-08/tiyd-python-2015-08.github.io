Title: Mac Specs and Setup

## Specs

All students must bring their own MacBook laptop. Your MacBook should have a minimum of 4 GB of RAM and 128 GB of hard drive space. Those are minimum specs, and I recommend getting 8 GB of RAM and a 256 GB hard drive, but that’s your choice to make. Any MacBook model (including Air and Pro) made in 2012 or after will work well. If you already own a Mac and it's older than that, send me an email and we can talk.

Your MacBook must be running OS X Yosemite. This is a free upgrade from the App Store.

There is no commercial software required for the class.

## Setup

As soon as possible after receiving your Mac, run through the following steps. If you've done a lot of your own configuration, some of these steps may have to change.  If you run into ANY PROBLEMS, send me an e-mail at:

<james.allen@theironyard.com>

Again, we want to have all of these kinks worked out in advance, so PLEASE e-mail if things don't work as described below.

* Install **OS X Yosemite**, if you haven’t already.
    1. You'll need to sign in to the Mac App Store with you Apple ID. If you don't have one, [sign up here](https://appleid.apple.com/).
    1. Download the Yosemite upgrade from the Apple Store: [download here](https://itunes.apple.com/us/app/os-x-yosemite/id915041082?mt=12).
    1. Double-click "Install OS X Yosemite” to begin installation.

  **WARNING:** The OS X upgrade can take a bit of time to complete and will require a restart. Plan on doing this in the evening or over a lunch break.

 * Install XCode Command Line Tools
    1. Open up Terminal.app. If you have any trouble here, go through [the command-line prework](/prework/exercises.html#the-command-line).
    1. Run `xcode-select --install` and click the **Install** button.
    1. Follow all prompts to get the command line tools installed.

* Install Homebrew and additional tools
    1. Open up Terminal.app.
    1. Run `ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"` and follow all the prompts.
    1. Run `brew doctor`
    1. Run `brew install readline git python3 direnv tree wget trash bash-completion`
    1. Run `sudo easy_install pip`
    1. Run `sudo pip install virtualenv`

* Install Atom
    1. Download Atom from [the Atom website](https://atom.io/).
    1. Unzip the downloaded file by double-clicking on it. (It may be unzipped for you already, depending on how you downloaded it.)
    1. Move the Atom application into your Applications folder.
    1. Run Atom.
    1. Once Atom has started, click the Atom menu and run **Install Shell Commands**.

* Install [Google Chrome](https://www.google.com/intl/en/chrome/browser/)

* Install some helpful dotfiles and terminal
    1. Open up Terminal.app.
    1. Run `git clone https://github.com/tiyd-python-2015-08/dotfiles.git`
    1. Run `./dotfiles/bin/dfm install`
    1. Exit Terminal.app and reopen it for the changes to take effect.