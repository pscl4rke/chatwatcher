

ChatWatcher
===========

When complete this project will provide a daemon that sits in
a Jabber chat room and then runs custom commands based on the
messages that come through the chat.

This project will have achieved its main goal when the office
bear can read out all messages (courtesy of ``festival --tts``).


Installation
------------

Ha!  That's still to be organised.  However I can tell you:

Requirements:

-   SleekXMPP (https://github.com/fritzy/SleekXMPP)


Usage
-----

The standard usage is::

    $ /path/to/chatwatcher /path/to/settings.cfg

An example config file is included in the repository.

Note that at this time it is still designed to be ran in a terminal,
and does not do any self-daemonisation.  Try detaching it in a
screen or tmux session instead.


