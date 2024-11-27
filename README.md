# Mayhem3Checks

Linux Xboard 3 and 5 checks Chess Engine.

![logo](https://github.com/user-attachments/assets/b7f182b0-5756-4989-8b36-72162795f951)


## Supported commands

```
Mayhem3Checks. Linux Xboard 3Checks Chess engine. Written in C++20 language

Supported commands:

help
  This help

ping [N]
  Responded by 'pong N'

level [movestogo] [time] [inc]
  Setup time control

random
  Add random element to eval

time [N]
  Setup time left for the engine

force
  Setup force mode. Act only after 'go' command

new
  Setup new game

list
  Show list of moves

play [ms = 5000]
  Watch a game

analyze
  Analyze position

undo
  Go back in history

.
  Respond ASAP

?
  Move ASAP

option
  Setup option in form of 'option hash=256'

variant
  Setup variant

setboard
  Setup board using FEN notation

logo
  Print ASCII art logo

p [fen = startpos]
  Print ASCII art board

perft [depth = 6] [fen = startpos]
  Calculate perft split numbers

bench [depth = 14]
  Show signature of the program

speed [ms = 5000]
  Show speed of the program

exit
  Exits the analyze mode

quit
  Exits the engine ASAP

```

## Sample game

```
[White "Mayhem3Checks 0.1"]
[Black "Mayhem3Checks 0.1"]
[Result "1-0"]
[TimeControl "60+1"]
[Variant "3check"]
1. e4 {+0,25/16} Nc6 {-0,47/16 3} 2. Nc3 {+0,27/16 3} e6 {-0,43/16 3} 3.
Nf3 {+0,59/17 3} Nf6 {-0,46/16 3} 4. a3 {+0,49/16 3} Be7 {-0,48/15 3} 5. d4
{+0,53/16 3} Ng4 {-0,48/15 3} 6. Bf4 {+0,53/14 2,9} O-O {-0,50/14 2,9} 7.
Qd2 {+0,83/15 2,8} d5 {-0,73/15 2,8} 8. e5 {+0,67/15 2,7} f6 {-0,66/14 2,7}
9. exf6 {+0,76/15 2,7} Bxf6 {-0,75/14 2,7} 10. O-O-O {+1,05/14 2,6} a6
{-0,82/14 2,6} 11. h3 {+1,63/15 2,5} Nh6 {-1,37/15 2,5} 12. Bd3
{+1,41/15 2,5} Kh8 {-1,42/16 2,5} 13. Bxh6 {+1,43/15 2,4} gxh6
{-1,32/15 2,4} 14. Qxh6 {+1,12/14 2,4} Rf7 {-1,22/15 2,4} 15. Rhe1
{+1,50/13 2,3} Bd7 {-1,60/12 2,3} 16. Kb1 {+2,01/13 2,3} Rg7 {-2,36/13 2,3}
17. Nxd5 {+4,48/15 2,2} Bg5 {-4,13/15 2,2} 18. Qxg7+ {+4,16/14 2,2} Kxg7
{-4,13/1 0,1} 19. Nxg5 {+4,59/15 2,1} Qxg5 {-4,60/15 2,2} 20. Nxc7
{+4,57/15 2,1} Kh8 {-4,83/15 2,1} 21. Nxa8 {+4,95/15 2,0} Qd8
{-5,09/15 2,1} 22. Bxh7 {+5,50/15 2,0} Qxa8 {-5,73/16 2,1} 23. d5
{+6,17/17 1,9} Ne7 {-6,30/17 2,0} 24. Re5 {+9,55/16 1,9} Be8 {-9,99/16 2,0}
25. Rd4 {+104,85/13 0,5} Qa7 {-104,85/12 0,4} 26. Rh4 {+104,85/9 0,1} Bh5
{-104,85/5 0,1} 27. Rhxh5 {+104,85/4 0,1} Qxf2 {-104,85/3 0,1} 28. Bd3+
{+104,85/2 0,1} Kg7 {-104,85/2 0,1} 29. Rh7+ {+104,85/1 0,1}
{Xboard adjudication: 3rd check} 1-0
```
