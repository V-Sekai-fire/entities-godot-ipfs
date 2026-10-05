# entities-godot-ipfs

A small game-engine project that runs a bundled IPFS node as a child process and fetches content by its link.

## What it is for

It shows a game client carrying its own content-addressed network node: the client starts the node in its user data directory, reads a pasted content link through the node's command line, and shuts the node down from its quit button. The node binaries for each desktop platform are bundled, and the script launches the Windows one.

## Build and run

The scene does not run as committed: `project.godot` is in the 3.x format and `Node2D.gd` mixes 3.x and 4.x calls, so neither engine version parses the script.

## Licence

MIT; see `LICENSE`. The bundled node binaries are under their own MIT licence in `IPFS.LICENSE`.
