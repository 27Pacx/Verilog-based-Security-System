# Digital Password Lock using FSM

A finite state machine (FSM) based digital password lock that lets a user
enter a predefined password using push buttons or switches. The entered
sequence is compared with a stored password. On a match, the system unlocks
by activating an LED or relay output. On a mismatch, the failed attempt is
recorded, and after three consecutive incorrect attempts the lock enters a
security lockout mode, blocking further entries until a reset or timeout.

## Concepts Covered
- Finite State Machine (FSM) design
- Registers for password storage and input capture
- Counters for tracking failed attempts and lockout timeout
- Comparator for password matching
- Button/switch debouncing
- Clock division for human-scale timing

## Features
- Configurable stored password
- LED/relay unlock output
- Failed-attempt tracking (3-strike limit)
- Lockout mode with reset or timeout recovery
