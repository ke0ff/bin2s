# bin2s
Binary to S19/S28 converter for WIN10
Visual CPP project for WIN10.  Beta release (V0.3).
Features a terse help response:

<pre>
C:\>bin2s -?
	Binary to S-record conversion utility, (c) 2024 Joseph Haas.
	Usage:  bin2s {in_name} / {out_name} / {-?}
	Valid {args}:
	{-?}      help
	{xx_name} any valid filename (include extension)
	If {out_name} is omitted, the default 'out.s28' filename will be used
	Output is S19 format unless input file is > 65536 bytes, in which case
	the output is in S28 format.

  Press any key to continue...
</pre>
Responds to file errors and provides terse reports of those errors.  The "EXE" zip archive is the compiled exe (runs out of a cmd window).<br>
The easiest use-case is to place the .exe into the folder with the bin files to be processed.  The output files will be created in that same folder.
