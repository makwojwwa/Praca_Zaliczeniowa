Game Mechanics <!-- omit in TOC -->
=
# Reactor structure
The reactor is composed of three parts: the **input area** to the left, the **output area** to the right and the area between them. In certain levels the input and output areas are sub-divided into α and β inputs and ψ and ω outputs, respectively.  
Below the reactor are various instructions that can be used by the player. They are described in detail in [Basic instructions](#basic-instructions). Simply click the required instruction and drag it to the desired location in the reactor.  
The player carries out various reactions with the use of **waldos**. There is a red and a blue one, so they can execute two different algorithms at the same time. The goal is to create paths for the waldos with the use of the available instructions so that the required chemical compound can be formed and output in the right area.  
The reactor most often contains also special objects, which are required for carrying out the reaction or executing the algorithm. These are bonder plates, sensors and fusion plates. They are described in detail in [Special objects](#special-objects).
# Basic instructions
## Start
The first and the most important instruction of all. It marks the place where the waldo begins executing the algorithm.
## Input
This instruction makes an atom or molecule appear in the input area, at the exact place as indicated in the small grid presented to the left of the reactor grid.
## Output
This instruction makes an atom or molecule disappear in the output area.
## Grab/Drop
There are three variants of the "GRAB DROP" button. The default one makes the waldo grab or drop an atom or molecule located exactly at the place where the instruction is located. The button can be switched to either "GRAB" or "DROP" so that the waldo can perform only one operation (grabbing or dropping) instead of the possibility to perform both.
## Rotate molecule
This instruction is responsible for rotating the molecule grabbed by the waldo 90 degrees clockwise or counter-clockwise.
## Bond+/Bond-
These instructions are variants of the "BOND +" button. "BOND +" creates a bond between atoms that are present on adjacent bonders, whereas "BOND -" destroys a bond between atoms that are present on adjacent bonders. The instruction need not be placed directly on bonders.
## Arrow instructions
The arrows force the waldos to change their direction in the reactor.
## Sync
"SYNC" is useful for avoiding collisions and making sure that both waldos execute their respective algorithms in the proper sequence. You have to place one "SYNC" for the red waldo and one for the blue one. The first waldo reaching its "SYNC" will stop there and wait until the other waldo reaches its "SYNC". Once this happens, the first waldo starts running again.
# Advanced instructions
# Special objects
## Bonders
There are four bonders in a reactor by default, although in some scenarios only two are available. Their task is to create or remove a bond between atoms placed on adjacent bonders. When the "BOND" instruction is executed, it affects all bonders at the same time.
## Sensors
## Fusion plates
# Assignments
## Reaction assignments
These are the basic assignments in the game. Their aim is to program a single reactor so that atoms or molecules can be input and modified in such a manner by the waldos that the required atoms or molecules can be output.
## Production assignments
These assignments require storage tanks or harvesters, one or more reactors, and cargo freighters. These objects are connected by pipelines. Storage tanks or harvesters supply molecules to reactors via pipelines. Reactors are connected to further reactors or cargo freighters via pipelines.
## Defense assignments
