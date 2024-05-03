# bin2s
Binary to S28 converter for WIN10
Visual CPP project for WIN10.  Beta release (V0.2).
Features a terse help response:

<pre>
C:\>bin2s -?
Usage:  bin2s {in_name} / {out_name} / {-?}
Valid <args>:
  {-?}      help
  {xx_name} any valid filename
  If {out_name} is omitted, the default "out.s28" filename will be used.
  File over-writes are NOT prompted!

Press any key to continue...
</pre>
Responds to file errors and provides terse reports of those errors.  The "EXE" zip archive is the compiled exe (runs out of a cmd window).<br>
The easiest use-case is to place the .exe into the folder with the bin files to be processed.  The output files will be created in that same folder.
