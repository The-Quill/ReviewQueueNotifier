# Review Queue Notifier [![Code Review](http://www.zomis.net/codereview/shield/?qid=98619)](http://codereview.stackexchange.com/q/98619/62429)

##This is a script for the Stack Exchange Network

This script will make it so that you are notified on the Desktop whenever new reviews are available, as long as you have a review tab open.

###How to use
- Install [Greasemonkey](http://www.greasespot.net/) (Firefox) or [Tampermonkey](http://tampermonkey.net/) (Chrome). These are userscript managers and allow the script to make use of `GM_*` functions
- Install the script: <kbd>[install](https://github.com/malachi26/ReviewQueueNotifier/raw/master/ReviewQueueNotification.user.js)</kbd> or <kbd>[view source](https://github.com/malachi26/ReviewQueueNotifier/blob/master/ReviewQueueNotification.user.js)</kbd>
- Any time you have a review queue window open, the script will run and alert you anytime there are reviews to be performed.

###Notes
- I will continue to make advancements with the code, so please keep an eye on this project by starring!
- Feel free to post issues to the GitHub repository, contributors actively watch for issues and will work on solving them ASAP!
- [Donate to future development!][1]

I altered a [zomis][2] script to create this version, [check out his Moderator version][3].

###Updates

Version 2.1.1

- Fixes issue where no notification would show up when using GreaseMonkey on Firefox-derived browsers.

  [1]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=7PTJ7V3ERTYWQ
  [2]: https://github.com/Zomis
  [3]: http://codereview.stackexchange.com/q/97268/18427