# Packet Captures from multiplayer games

### PlayStation

Regarding the PlayStation packet captures, they are encrypted via Medius (SCE-RT).

Medius uses the RCQ algorithm and Textbook RSA to encrypt messages.

Here's documentation on PlayStation 2 Medius and Ratchet & Clank 3:

- RCQ: https://wiki.hashsploit.net/RCQ
- PlayStation 2: https://wiki.hashsploit.net/PlayStation_2
- UYA Protocol: https://wiki.hashsploit.net/Ratchet_and_Clank_3:Protocol

Here's a few libraries that handle attempting to decrypt those packets:

- Java: https://github.com/hashsploit/medius-crypto
- C#: https://github.com/Dnawrkshp/medius-crypto
