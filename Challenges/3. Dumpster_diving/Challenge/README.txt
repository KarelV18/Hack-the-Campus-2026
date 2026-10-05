Case File 03: Dumpster Diving
Like any good university student, you come across a desktop PC being thrown away and rescue it from its grim fate. While examining the computer, you discover software used in a small and specialised market. More importantly, records on the machine suggest that the server may have been connected to the recent activity involving 0xGhost.
You soon realise that this was not an ordinary client computer. It was a server that may once have been exposed to the internet and potentially vulnerable to remote attacks. Several crash dumps are still stored on the machine, which may reveal what the server was doing and how it was compromised.
However, there is one problem: the crash dumps are encrypted. It appears that whenever the server crashed, it captured its memory and encrypted the resulting dump before sending it to the developers for analysis.
A command-line program called DumpPrepper was also recovered. The program accepts a filename and appears to encrypt it using the same method.
Reverse engineer DumpPrepper, decrypt the crash dump and determine what 0xGhost left behind.
Flag format: MDXFlag{...}