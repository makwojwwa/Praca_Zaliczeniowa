# General
* You can move the "START" instruction wherever you want. You can change the direction of the "START" instruction. You don't have to end your loop on the "START" instruction.
* You don't have to use both waldos - sometimes one is able to execute the algorithm.
* It is a good idea to place bonders on the input.
* The actual shape of the molecule to be output is not important.
* Each waldo cen move through a single grid cell from two directions, at the right angle.
* Bonders have numbers, which give them priority. This means that e.g. bonds will be created first between bonder 1 and bonder 2 than between bonder 1 and bonder 3 if all of them are adjacent to one another. This is very important because sometimes you will want to create a bond on a specific side of an atom rather than on a different side.
# Production assignments
* The molecule output in a reactor will appear in the next reactor in the exact position on the grid in which it was output. Clever planning of the position of output molecules can make it easier to create new molecules in the downstream reactors.
* Molecules need some cycles to reach the reactor after leaving the storage or the previous reactor. Sometimes you have to adjust the length of the pipelines to avoid jams.
* Plan in advance which intermediate molecules you want to create. This will help you decide how many reactors and in what configuration should be used.
# Defense assignments