# Troubleshooting

## Bonding
| Problem | Possible cause | Solution |
| :------------- | :------------- | :--------------- |
| Bonds are still present | Too few BOND - instructions | Add more BOND - instructions |
| | Bonders do not support bond removal | Replace reactor with Disassembly Reactor |
| Bonds are not added | Bonders do not support bond additions | Replace reactor with Assembly Reactor |
| | No more bonds can be added to this particular atom | Remove some bonds earlier or get a different atom |
| Bonds are added not between desired atoms when all bonders are placed adjacent to one another | Bonder priority was triggered | Check bonder numbers and switch their places to achieve required bonding |
## Outputting
| Problem | Possible cause | Solution |
| :------------- | :------------- | :--------------- |
| Molecule is not output | Molecule was not dropped | Drop molecule
| | Molecule was not dropped entirely in output area | Drop molecule entirely in output area |
| | Molecule was dropped in inactive output area | Drop molecule in active output area |
| | Wrong instruction was placed (e.g. OUT ψ instead of OUT ω) | Place correct instruction |
## Collisions
| Problem | Possible cause | Solution |
| :------------- | :------------- | :--------------- |
| Atoms collide inside reactor | Waldos are on collision course | Re-route waldos |
| | | If re-routing is impossible, add SYNC instructions to change timing of each waldo |
| | Atoms/molecules were not dropped | Drop atoms/molecules at required places |
| | Jam in downstream reactor | Remove jam by extending relevant pipeline |