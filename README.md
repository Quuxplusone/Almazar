## Almazar (Winston M. Llamas, 1981)

This game was on the RPI computer system around the same time as
[_Castlequest_](https://github.com/Quuxplusone/Castlequest/).
It was written in BASIC by Winston Llamas, a computer science student at RPI.

The maximum score is 90 points.


### Liddelow-1983/

The .BAS, .0, and .DOC files in this directory were downloaded from "sigm VOL142"
http://oldcomputers.dyndns.org/public/pub/cdrom/oak.oakland.edu/sigm/vol142/
on 2021-05-06.
`almazar.doc` (which is a plain text file) contains the original README.
These files were slightly modified by Robert I. Liddelow (1983-05-16), to work
on the Osborne-1 microcomputer, and at least to slightly modify the help text.

Arthur O'Dwyer modified the files a bit further in order to run on a modern
emulator; check the git history for details.

The MBASIC interpreter, `mbasic.com`, was downloaded from
http://www.retroarchive.org/cpm/lang/mbasic.zip
on 2021-05-06.

To run the game:

- Download iz-cpm 1.0 from https://github.com/ivanizag/iz-cpm/releases

- Run `iz-cpm --disk-a . mbasic.com` from this directory.

- In the emulator, type `load "ALMAZAR.BAS"` (the ALL-CAPS filename is significant),
    then type `run`.

- To exit iz-cpm, if you're at the MBASIC prompt, type `system` to exit cleanly.
    Otherwise, or if you're in a hurry, hit Ctrl-C twice to hard-exit from iz-cpm.


### 80Micro-1983/

This is a scan of part of "80 Micro" magazine (ISSN 0744-7868)'s
1983 Special Anniversary Issue, downloaded from
https://archive.org/details/80-microcomputing-magazine-1983-SE/page/n287/
(The 1983 Special Anniversary Issue was 594 pages in length.)

The BASIC source code listing was submitted by Winston Llamas himself.
The accompanying description states: "This version of Almazar was
designed for a one-drive 32K Model III."


### Model-III/

The zip file in this directory was downloaded from "The Humongous CP/M Software Archives,"
in the "TRS-80 Model III" directory
http://cpmarchives.classiccmp.org/trs80/Software/Model%20III/
on 2021-05-06, and then unzipped to produce the file `srchalm1.dsk`.


### John-Wesson-notes/

The PDF file in this directory was received via email from
John P. Wesson (RPI 1971, 1976, 1988) on 2021-05-06; it contains
a hand-drawn map of _Almazar_.
