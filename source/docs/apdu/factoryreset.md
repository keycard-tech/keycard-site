---
id: apdu_factoryreset
title: Protocol
---

# FACTORY RESET

* CLA = 0x80
* INS = 0xFD
* P1 = 0xAA
* P2 = 0x55
* Response SW = 0x9000 on success

Resets the card to its uninitialized state. This deletes all stored keys, pairing information, and user data. There is no way to get the information back.
