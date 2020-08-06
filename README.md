# Sounds Legit: Why you shouldn't trust that speaker

BadUSB devices are popular worldwide, and almost no one ignores their nature: an object with a USB connection (usually a pendrive) connects to a computer and tells it "I am a keyboard", proceeding to send ("type") arbitrary commands, usually malicious.

In this talk we have decided to go beyond the classic concept of a malicious pendrive.

We use a set of classic USB speakers from a well-known brand available worldwide, which we disassemble to add our own hardware modification.

This modification, which consists of cheap parts that can be acquired worldwide, makes this set of speakers an unprecedented local and remote attack vector: a device that looks and functions as a speaker, but is capable of acting as a keyboard, exfiltrate information, and use a SIM card to receive remote commands by telephone to leak information.

When connected, the speaker passively waits for a phone call to its internal SIM from a specific number. Upon receiving it, launches a payload against the computer to which it was connected, allowing the attacker to obtain a shell.

Now then, what would happen if someone left this speaker in its original box in a corner of an office?

What would happen if someone connected this innocent device to their work terminal?

Well, it is a speaker after all. And it definitely sounds legit...


## Conferences

|#| Date | Conference | Link to Video | Link to Slides |
|---|---|---|---|---|
|1| AUG-2020 | DEF CON 28 Red Team Village | - | https://docs.google.com/presentation/d/1ER3G_9c_L1Yz91RhJCEtWcL0UTbko90dQu5Ov09TqXE/edit?usp=sharing |

## Credits

**Sounds Legit** is our second talk @[dc5411](https://github.com/dc5411). It was authored by Luis Ángel Ramírez Mendoza, Farith Pérez Sáez and Mauro Eldritch.
