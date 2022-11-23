# Project Minecraft

Currently all projects are made to work with minecraft 1.18.\*/1.19.\*

Projects are inspired and created to solve challenges based on [LiveOverflows](https://github.com/LiveOverflow) youtube series [Minecraft Hacked](https://www.youtube.com/watch?v=Ekcseve-mOg&list=PLhixgUqwRTjwvBI-hmbZ2rpkAl4lutnJG) which inspires the audience to learn reverse engineering, vulnerability research and working with opensource projects.

## Bedrock scanner

Rust project capable of scanning ~43.8m chunks per second / ~11.2b blocks per second for specified bedrock formation. Also can scan for seed based on given bedrock position and x|z value.

## Minecraft server masscanner

Python project which utilizes [masscan](https://github.com/robertdavidgraham/masscan) to scan batches of ip-ranges for specific open port and multithread ping them for active minecraft servers. Results are stored neatly in [mongodb](https://www.mongodb.com/) database.

## Raviomod

Minecraft [Fabric](https://github.com/FabricMC) utility mods created by me which include exploits for challenges on the server.
