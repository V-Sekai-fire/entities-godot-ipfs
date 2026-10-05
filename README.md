# entities-godot-ipfs

A small game-engine project that runs a bundled IPFS node as a child process and fetches content by its link.

## What it is for

It shows a game client carrying its own content-addressed network node: the client starts the node in its user data directory, reads a pasted content link through the node's command line, and stops the node when it quits. The node binaries for each desktop platform are bundled, and the script launches the Windows one.

## Build and run

Open `project.godot` in the engine's editor and run the main scene.

## Licence

MIT; see `LICENSE`. The bundled node binaries are under their own MIT licence in `IPFS.LICENSE`.
