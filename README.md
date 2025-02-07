# libtoontown-python
The modules for libtoontown and libotp ported as Python modules over a C module

# Reworked DNA System
The DNA system in the repository is a very close to replica of libpandadna developed by loblao, except it is written in Python, removing the use for Toontown projects like TT Archipelago, and ESPECIALLY Open-Toontown, from using a specially built Panda3D with the DNA system built into the game engine.

The new DNA system (like libpandadna) uses compiled DNA files (.pdna), which are converted from raw DNA files (.dna), to convert your raw DNA files, use the compiler listed [here](https://github.com/loblao/libpandadna/tree/master/compiler) to convert your .dna files to .pdna files, you CANNOT use .dna files with the DNA system in this repository, it is simply NOT supported and will crash you.
