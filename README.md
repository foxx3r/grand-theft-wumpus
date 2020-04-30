# grand-theft-wumpus
That's a game like GTA, it's based on game "Hunt the Wumpus".

To play that game, run on SBCL on CLISP:

`(load "game")`

Now, generate the map:

`(new-game)`

And then, load the city.png whether you don't want to see the full map, or load the unknown-city.png, then, reload while you're executing the functions.

To see your current location, you'll need seeing city.png, and then, you can exexute these functions:

- walk
- charge

You have only one bullet, it's what charge does. This one bullet is for kill wumpus. If you shot them, you will win, else, you will lose. You have clues around the map, as you can see:

- blood => glowworm's gang
- light => wumpus
- sirens => cops

Those all are your enemies.
