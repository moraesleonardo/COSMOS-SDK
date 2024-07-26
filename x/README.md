# `/x/rps` - Rock, Paper and Scissors Module

This directory contains the code for your chain custom modules.


## State objects


### Game

- gameNumber (int)
- playerA (address)
- playerB (adress)
- status (string)
- rounds (uint)
- playerAMoves([]string)
- playerBMoves([]string)
- score ([2]uint)


## Msg service


#### MsgCreateGame

- creator (address - signer)
- oponent (address)
- rounds (uint)

### MsgMakeMove

- player (address - signer)
- gameIndex (uint)
- move (string - Rock, Paper, Scissors)


## Query Service

### GetGame

- gameNumber(uint)



