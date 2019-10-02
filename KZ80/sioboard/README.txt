SIO/2-based serial console
==========================

This is based on the RC2014 SIO/2 board from Spencer Owens [1]. It's
been adapted specifically to mount on top of the KZ80 mainboard.

|======+=========|
| Port | Address |
|======+=========|
| A/C  |     $80 |
|------+---------|
| A/D  |     $81 |
|------+---------|
| B/C  |     $82 |
|------+---------|
| B/D  |     $83 |
|------+---------|

A = SIO A
B = SIO B
C = CONTROL
D = DATA
