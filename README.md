# mtgtools
Programming tools related to Magic: the Gathering

## gameview
The file `gameview.json` defines a [JSON schema](http://json-schema.org/) for JSON files that can describe a *view* onto a Magic: the Gathering game. Note that such a file would not contain sufficient information to accurately reproduce all elements of the game state; rather, it encompasses the elements a player (or spectator) needs to be able to follow and play the game. Many elements are included that would not be visible in a paper game of Magic, such as the current colours of permanents and mana pools (including any riders attached to the mana).
