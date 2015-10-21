Codex Apocalyptica
==================

This project is an attempt to create a lore-driven beginner's guide to the game Cataclysm: Dark Days Ahead. It is written in the form of a Codex originally penned by an unnamed survivor, passed down and ammended by dozens of others. It seeks to introduce the game's interface, mechanics and provide some amount of early-game strategy. The hope is that it draws in more players and makes the game more accessible.

It is implemented ontop of a Python static-site generator called Pelican.


Pre-requisites
--------------

To install Pelican and its dependencies you'll need a Python installation with Pip:

    pip install pelican markdown typogrify

In order to build the SASS CSS files you'll need to install Ruby Gems and SASS:

    sudo su -c "gem install sass"


Building
--------

To build the site locally, simply run the `develop_server.sh` file:

    ./develop_server.sh

It will fork into the background. To watch for changes to SASS CSS files and rebuild them:

    sass --watch themes/cait/static/css/sass/:themes/cait/static/css/


Contributing
------------

To contribute, simply fork the repository, and make changes to the `content` branch. Submit a pull request and when it is merged it will appear on the site. The `master` branch contains the built site, as per how github-pages works.

