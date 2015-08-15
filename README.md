# vim-adventures
solutions to puzzles in Vim Adventures

---

### Readme
[Vim Adventures](http://vim-adventures.com/) is an excellent educational game by Doron Linder.  It focuses on teaching many popular commands and motions used in the [Vim](http://www.vim.org/) text editor.  Here are a few disclaimers: 
- My solutions may not be the only way, and may not even be the optimal way to solve the puzzles.
- I strongly suggest you attempt all levels on your own before turning to the following spoilers.

### Levels
#### Level 8
- last puzzle: 
   - start on first twin brother, `j # E # n n ^ k $ * j j`, end on second brother

#### Level 9
- puzzle to the right: 
   - start on 'N' `$ j j j` end on 'd', get key
   - to go back, start on 'd' `gg`
- use key to enter house and get ability to use all numbers
- puzzle below the house (with 11 key presses):
   - start on 'n', which is numbered with a red '1'
   - you should visit the blocks in numerical order
   - `4j` → `b` → `2k` → `3w` → `4$` → `Tu`, you are now at the space on the other side
   - the key has appeared at the beginning of this puzzle, lets go back to get it
   - starting at the space, `5G` → `to` → `4k` 
   - now we have the key and can go back again to the bottom side of this puzzle, using the original way we came
- puzzle down and to the right of the last puzzle (with 8 key presses):
   - start on the 'f', which is numbered with a red '1', and we will again go in numerical order
   - `fi` → `3*` → `Fu` → `2*`
   - we are now at the other side on the 's' of 'sum', follow the path down to the '.' on the morse code looking puzzle
- morse code puzzle (spells out 'VIM ADVENTURES' in morse code):
   - `3e` gets directly to the other side
   - go down to lolcat sounding puzzle
- lolcat puzzle (16 key presses)
   - starting on 'W', `3x  ~  j  5~  5j  d4j  fC  2rG`
   - the key appears at the beginning of the puzzle, `6k` to go back up to get it
   - go back up through the morse code puzzle, `3e  k  5f.`
   - starting on 's' of 'sum', go back through this puzzle, `2G`
   - go left to '.' of next puzzle
- puzzle left of pink haired girl in bush (4 key presses)
   - starting on '.', `16b` (probably not the best answer to this puzzle)
   - go up to puzzle with a whole lot of numbers (actually just one number, Pi, to a whole lot of decimal places)
- Pi number puzzle (7 key presses)
   - start on '8', `9G  2f8  4k`, end on broken '5' tile
   - key appears on last '8', get there with `11G  6l  4j  3l`, we now have 3 keys
   - and back to the start of the puzzle with `3h`
   - go down to previous puzzle on 'k'
- puzzle below Pi puzzle (4 key presses)
   - start on 'k' of 'keep', `3$  Fa`, end on 'a' above locked gate - NOT CORRECT

