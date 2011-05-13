Quick Start
-----------

No very much have to be done to start using Tyrs, just start `tyrs/tyrs.py`.
With the Twitter Oauth authentification, you'll need to autorize the
client to access your account, just start it, and follow the link
display by the prompt. Accept it, and return the pincode in the
prompt. **You must be logged in to your web browser before**

This step will create automatically a file to store you're *token* in
your home `~/.config/tyrs/tyrs.tok`.

That's all, you can now see your tweets display in the terminal.

Usage
-----

* Navigation
  * Move down  : j or down arrow
  * Move up    : k or up arrow

* Functions
  * Tweet      : t
  * Retweet    : r
  * Quit       : q
  * Clear      : c
  * Update     : u

* Tweet edition
  * Abord      : ESC
  * Send       : ENTER
  * Delete     : DEL


Configuration
-------------

You can add a configuration file, there is no need to have one to get
it work, but you can customized some keybinding, color and basic
behavior.

The configuration file should be place in `~/.config/tyrs/tyrs.cfg`

For a full exemple with comments of a configuration file, check the
`doc/tyrs.sample.cfg`.

Related Sites
-------------

- Github:     https://github.com/Nic0/tyrs
- BugTracker: https://github.com/Nic0/tyrs/issues
- First Blog post: http://www.nicosphere.net/tyrs-premier-jet-dun-client-twitter-ncurses-2361/
- My Blog:    http://www.nicosphere.net