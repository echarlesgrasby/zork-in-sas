# Research

This file is a running document that includes all of my background research on how Zork was implemented (including the eponymous ZIL: "Zork Implementation Language").
I use this as a reference for how I can make a Zork-inspired clone in SAS. 

## Structural Concepts

### Control Variables

The most important control variables in ZIL appear to be: PRSA, PRSO, and PRSI; these stand for "PaRSer Action", "PaRSer Object", and "PaRSer Indirect object", respectively.
The idea here is that a natural language parser parses player input into key commands that can drive the game logic (think an SVO language like English), "ATTACK" the "MAILBOX" with the "SWORD"[^1].

* PRSA - Bound to an action. Examples include "TAKE", "LOOK", "GO"
* PRSO - Bound to an item/object in the game environment. Examples include "LETTER", "MAILBOX", etc.
* PRSI - Bound to an indirect object in the game environment. "SWORD" in the example sentence above.

## References

[^1]: Ajdnik, Rok. July 2020. [Zork: The Great Inner Workings](https://medium.com/swlh/zork-the-great-inner-workings-b68012952bdc)
