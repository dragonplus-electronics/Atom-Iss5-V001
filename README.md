# Atom Iss5 Repro V001 (Near Replica)
 This board is intended to be used as a replica Issue 5 board for the Acorn Atom. If you build it, please share your experiences via Stardot or other Acorn Atom online forums.

 ## KiCad File Content
 
 Wherever possible, custom symbols have been created in order to align closely to the structure of the original Atom schematics. The schematic itself though has been split into logical areas with off-sheet address and data busses as well as global pin assignments. When you open the project, you will likely need to 'Rescue' the symbols, as you will not have the custom libraries.
 
 The PCB files themselves are not included in this repository, purely because at this stage I do not want people running off and creating all sorts of forks and modified boards. Please do not ask me for them, as refusal often offends. :) Those files will follow once all Atom repro work is concluded.
 
 Although the PCB is close to identical in most respects, including the aesthetics of the silkscreen etc, certain elements have been changed in order to facilitate sourcing/placement of certain components. These are listed below:
 
 ## Footprint Changes
   - Links 1-3 & 6-7 have been modified so that they are joined using a 2.54mm pitch header, instead of non-standard length links of wire.
   
   - SK1 - the power socket has been switched for a modern footprint. Suitable sockets are the Cliff FC681465 or the FC681478. The former will accept both 2.1mm and 2.5mm barrel jacks, whilst the latter will only accept 2.1mm barrel jacks.
   
   - SK2 - this has been swapped for a modern DIN-7 socket footprint. These are readily available. One such example is: https://uk.farnell.com/pro-signal/psg03465/din-socket-pcb-7p/dp/1791759
