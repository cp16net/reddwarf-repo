reddwarf-repo
=============

Reddwarf Collection of Resources using Repo

Getting started with this Repo
------------------------------

#. Setup _repo_ on your machine::

    $ mkdir ~/bin
    $ PATH=~/bin:$PATH

#. Download the Repo script and ensure it is executable::

    $ curl https://dl-ssl.google.com/dl/googlesource/git-repo/repo > ~/bin/repo
    $ chmod a+x ~/bin/repo

#. Create a new directory for the repo::

    $ mkdir ~/reddwarf-repo
    $ cd ~/reddwarf-repo

#. Initialize your repo::

    $ repo init -u git://github.com/cp16net/reddwarf-repo.git

#. Synchronize your repo now::

    $ repo sync

#. Profit...


More information about repo:

http://source.android.com/source/version-control.html

