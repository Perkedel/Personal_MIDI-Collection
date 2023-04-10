This folder contains "corrupted" MID files and my attempts to repair them.
.mid.dat files are the original versions from the collection.
.mid.header.dat files are extracted versions of any bytes that were in the .mid.dat files before the MThd magic number.
.mid files are the same as .mid.dat files, but with the contents of .mid.header.dat chopped off.
This process fixed every MID file except for Africa03.mid. I believe it may be actually corrupted. However, I may be wrong. Someone who knows more about the .MID file format than me is welcome to take a crack at it.
The files in the folder corruption are clearly corrupted. They had nothing before MHdr, a likely corruption of the MTHd magic number. They may be salvagable, but I don't have the expertise to do so.
memory_of_trees.mid.dat has all the right makings of a .MID file... except for the MThd magic number. It should be an easy fix for someone more experienced in the .MID file format.