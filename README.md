# lu-grim
LEGO Universe, but as an ARPG.

## Install (Server)
Compile [Infected Rose](https://github.com/Wincent01/InfectedRose).

Build DLU with [this](https://github.com/DarkflameUniverse/DarkflameServer/tree/grim-lu) branch.

In your client, create a `mods/` subdirectory beside the `legouniverse.exe`.

Within `mods/` pull this repo, so that `grim/` is a subdirectory for `mods/`.

Run Infected Rose with the working directory being the `mods/` folder.

On the server, symlink `build/resServer/CDServer.sqlite` to `mods/CDServer.sqlite`.

On the server, symlink all the files within the `mods/grim/server/` directory to the `build/` directory.

To make sure players has the same identifers in the client, share the `mods/lookup.json` with the clients.

Start the server.

## Install (Player)
Compile [Infected Rose](https://github.com/Wincent01/InfectedRose).

In your client, create a `mods/` subdirectory beside the `legouniverse.exe`.

Within `mods/` pull this repo, so that `grim/` is a subdirectory for `mods/`.

Place the `lookup.json` that you got from the server operator witnin the `mods/` directory.

Run Infected Rose with the working directory being the `mods/` folder.

Start the client.
