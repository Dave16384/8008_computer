For many years I had been interested in building a computer using the the Intel 8008 microprocessor.
Finally I had the time to revisit my wish. A search turned up Jim Loos' 8008 Single Board Computer, 
https://github.com/jim11662418/8008-SBC. Here was working hardware and most importantly, a monitor 
and a high level language! Jim had built upon the work of Len Bayles's http://www.8008chron.com and 
Jim Kearney's 8008 computers https://www.jkearney.com/Tiny8demo. Credit for resurrecting SCELBAL BASIC
goes to Mike Willegal http://www.willegal.net/scelbi/scelbal.html. Thank you Alfred Arnold for the 
AS Macro Assembler http://john.ccac.rwth-aachen.de:8000/as/. Also, Dr. Scott Baker www.smbaker.com
has done some really neat 8008 work!

My first pass was a nearly exact copy of Jim's SBC with some modifications. Some parts were different 
based on what I had on hand. I chose to use Len Bayle's alternate clock design. Just something about 
tweeking pots while watching the pulse widths on a scope! I included several options to generate the 
-9v for the CPU.

I briefly considered wire wrapping the board, but decided that it would be less work if I taught
myself KiCad. The first board worked the first time I turned it on! I made a second version which is 
best forgotten.

The picture is version 3. I added an I/O bus and small I/O boards, along with some more circuit
modifications. Version 3.1 will be coming with a few minor tweeks, mostly in the silkscreen.

I measured the temperature of the 8008 as 35 degrees C above still air ambient. Adding the heat sink 
and fan reduced the temperature rise by 24 degrees C. Much better!


