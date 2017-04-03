Static Website Template for Puma-dev
====================================

Static website template for Puma-dev


## Qucikstart

### Prepare

if Pow is installed, uninstall it

    % curl get.pow.cx/uninstall.sh | sh


Then install and set up puma-dev

    % brew install puma/puma/puma-dev
    % sudo puma-dev -setup
    % puma-dev -install


### Install Static web template

    $ git clone git@github.com:tokzk/static-web.git
	$ mv static-web example
    $ cd example
	$ bundle install


### Create Puma-dev link

    $ puma-dev link
	$ open http://example.dev/


### View Puma-dev log

    $ alias puma-log='tail -f ~/Library/Logs/puma-dev.log'
    $ puma-log
