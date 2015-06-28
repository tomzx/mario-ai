# MarI/O AI

An implementation of [Neuroevolution of Augmenting Topologies](https://en.wikipedia.org/wiki/Neuroevolution_of_augmenting_topologies) for Super Mario games.

Changes I've done to the initial implementation:

* Minor improvement in test speed by detecting when mario dies and loading a state immediately
* Save/load game state in order to learn from various parts of the game
	* Save failure as died/timedOut. Timed out instances are re-used to learn more quickly.
* Load/Save all files in a specific folder instead of directly in the Lua folder.
* Fix saving issues when using the form Save/Load buttons.

Taken from [http://pastebin.com/ZZmSNaHX](http://pastebin.com/ZZmSNaHX).

Credits to SethBling