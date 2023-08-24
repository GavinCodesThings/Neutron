# Neutron
Neutron is an advanced anti-cheat solution for Minecraft Java Edition (1.8.8) Bukkit servers. This repository is made in specific for reporting bypasses and bugs, you can do so by creating an issue.

## Very cool things we offer
Neutron is almost fully packet based, meaning it monitors every packet going from the player's client to the server.

Neutron also has movement data for most types of movement (walking, sprinting, blocking, swimming, etc.), making it way more difficult to bypass than other anti-cheats.

Neutron is going to be 10 USD when it is released, where people will most likely be able to afford it.

Neutron is designed to account for ghost blocks (ex: if you jump on a ghost block after you place it and it disappears, you won't flag).

Last but not least, it lets you know the client brand of a player when they join

## Things to remember
Neutron requires you to have ProtocolLib in the server's "plugins" folder.

People who do not send transactions within a certain time frame will be kicked.

## Checks that will prob be added
Movement - Speed (A) (Prevents players from using any modules that increase their speed)

Movement - Flight (A, B) (Prevents players from using any modules that will allow them to fly)

Movement - NoSlow (A, B) (Makes sure that players slow down when they block their sword)

Packet - Post (A) (Prevents players from sending different packets after a movement in one tick)

Packet - InvalidPackets (A, B, C, more coming soon xd) (Prevents players from sending bad packets)

Packet - InvalidMovement (A) (Prevents players from moving WAY too fast using one packet)

Packet - GroundSpoof (A) (Prevents players from spoofing their packet's onGround to true)

Player - NoFall (A, B) (Makes sure that players get fall damage after falling 3 or more blocks down)

Combat - Killaura (A, B) (Prevents players from using the Killaura/Aura module)

Player - Scaffold (A, B, C, D) (Prevents players from using modules to automatically bridge)

Player - BedBreaker (A) (Prevents players from breaking beds through blocks)

Player - Timer (A) (Prevents players from speeding up their game)

Combat - Velocity (A, B) (Prevents players from reducing their knockback using velocity)

Combat - Reach (A) (Does raycasting stuff to make sure players dont extend their reach)

## Progress
Gathering data for prediction checks