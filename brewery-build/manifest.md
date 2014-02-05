Miscellaneous
=============

Requirements:

* Step bit - 1 1/4" at least
* Element wrench
* Labeler

Controller / Electric
=====================

This initial version is a very basic, almost entirely manual controller.
It needs to be able to control the various electrical components with switches, and little more.

I have two distinct circuits - one 240V/30A supply for heating, and one 120V/20A for pumps and other bits.
These will be wired entirely separately in this phase.

Miscellaneous
-------------

These are consumables involved in the project.
Most of these are bulk purchases far in excess of what's required for this project.
Tools aren't included here.

### Prices ###

* THHN Black / Green / Red / White 10ga wire - Lowes = $18 x 4 = $76
* THHN Black / White - Lowes = $15 x 2 = $30
* Cat5 for signals - Lowes = 250' for $37
* 10ga ring terminals - Phillips = $3
* 12ga spade terminals - Phillips = $3

Pump Control
------------

This is a simple 2-gang outlet box with two switch/outlet combo devices.
Unfortunately, these devices are not available in a 20A form, but my supply is 20A.
Safety would dictate that they be fused down to 15A, but since this is a temporary setup and inline fuses are hard to find, we'll let it slide.
Power comes from a regular straight-blade NEMA 5-20P.
The upstream supply is GFCI-protected.

Attaching the cable is a little tricky, since PVC conduit is intended to carry cable internally and terminate into other boxes.
The best solution seems to be a female threaded adapter and an appropriately sized cable gland.

### Prices ###

Total: $52

* 2-gang 1/2" FSE PVC box - Lowes = $5
* 2-gang PVC faceplate - Lowes = $3
* 2x 15A switch/outlet combination - Lowes = $9 x 2 = $18
* Short length 1/2" conduit - Lowes = $1
* 1/2" to 1/2" female threaded adapter - Lowes = $1
* 1/2" thread cable gland - Lowes = $1
* 8' 12-3 (H/N/G) SJOOW - Lowes = $10
* 8' 1/2" expandable sleeving - Amazon = $4 (partial from 50')
* 2x 3/4" x 4" heat-shrink - Amazon = $1 (partial from 10')
* 5-20P straight blade plug - Amazon = $8

Element Control
---------------

A three-way switch controls which of the two elements is active: the brew kettle (5500W / 240V) or the hot liquor tank (1500W / 120V), with the middle position not connected.
This switch drives contactors suitable for the high current to the elements.
The HLT hot lead also has an SSR in series with the contactor, connected to an STC-1000 temperature controller.

All of this is contained in a PVC junction box.
These boxes conveniently have no knockouts or penetrations, so they can be cut and drilled as needed.
I haven't found information on their NEMA rating, but they do ship with a gasket, giving at least some resistance to water penetration.

### Prices ###

Total: $187

* 8"x8"x4" PVC junction box - Lowes = $22
* 3/4" PVC box adapter - Lowes = $1
* 3/4" PVC to 3/4" female threaded adapter - Lowes = $1
* 3/4" threaded cable gland - Lowes = $1
* 10A DIN-mount Breaker - oscsys = $5
* 25A SSR - Amazon = $12 w/ sink
* SSR Heat Sink - included
* 12VDC supply - have
* STC-1000 temp controller - have
* 2P 63a DIN-mount contactor - oscsys = $25
* 1P 25A DIN-mount contactor (extra pole unused) - oscsys = $16
* L14-30P twist-lock - Amazon = $16
* 8' 10-4 (H/H/N/G) SJOOW - Lowes = $16
* 8' 1/2" expandable sleeving - Amazon = $4 (partial from 50')
* 3/4" x 4" heat-shrink 2pk - Amazon = $1 (partial from 10')
* 3-way 10A switch - ebrewsupply = $5
* 2-way 10A key switch - ebrewsupply = $5
* Green 220V LED - ebrewsupply = $3
* REd 120V LED - ebrewsupply = $3
* REd 220V LED - ebrewsupply = $3
* DIN Rail - oscsys = $4 (12")
* L14-30R twist-lock - Amazon = $19
* L5-20R twist-lock - Amazon = $15
* Round metal faceplages - Amazon = $5 x 2 = $10

Vessel Connections
------------------

The electrical connections for the vessels are similar: 

### Prices ###

Total: $59

* Brew Kettle Connection
  * L14-30P twist-lock - Amazon = $16
  * 8' 10-3 (H/N/G) flexible cord (SJOOW) - Lowes = $15
  * 8' 1/2" expandable sleeving - Amazon = $4 (partial from 50')
  * 3/4" x 4" heat-shrink 2pk - Amazon = $1 (partial from 10')

* HLT Connection
  * L5-20P twist-lock - Amazon = $8
  * 8' 12-3 (H/N/G) SJOOW - Lowes = $10
  * 8' 1/2" expandable sleeving - Amazon = $4 (partial from 50')
  * 3/4" x 4" heat-shrink 2pk - Amazon = $1 (partial from 10')

Stand (DONE)
============

This is assembled as follows, to allow gravity feeding from HLT to MT:

      HLT
    +-----+
    |     |  MT    BK
    +-----+-----+-----+
    |     |P   P|     |
    +-----+-----+-----+

With the lower tier about 2.5' tall and the upper about 4.5' tall.
This system can easily accomodate the uneven floor in my basement.

### Prices ###

Total: $92

* Joints - Lowes = $20 x 2 = $40
* 13 8' 2x4's - Lowes = $4x13 = $52

Connections
===========

Pumps
-----

Features:

* high-flow march pumps with polysulfone head
* full-flow ball valve + F-QD on output
* F-QD on input
* Mounted below vessel lower level for proper priming

Need two, to allow recirculation in HLT while recirculating mash.

### Prices ###

Total: $143 (have one set)

* Pump - ryan = $135 (agreed)
* Ball valve - ryan = free w/ pump
* 2x F-QD - $4 x 2 = $8

Hang-on Filler
--------------

Hangs over the side of a vessel to inject water from above.
For mashing, need one to recirculate hot liquor and one to recirculate wort.
For transferring, need one for boil keettle.

### Prices ###

Total: $28

* F-QD (MPT) - brewhardware = $4
* Platic Loc-Line (MPT) - brewhardware = $20
* 1/2" NPT coupling (FPT) - brewhardware = $4

HERMS Tube
----------

The first attempt is to use the existing copper wort chiller.
The existing thermoplastic hose will be adapted with female QD's to attach to a pump and the filler.

### Prices ###

Total: $38

* Copper coil, 3/8" OD 1/4" ID(?) - have
* Hand Clamp - Lowes = $3
* Cutting board to brace against clamp - Amazon = $7
* 3/8" hose - 1/2" MPT - Amazon = $3 x 2 = $6
* (UNNEEDED) 3/8" FPT to 1/2" MPT bushing - brewhardware = $4 x 2 = $8
* D-QD - brewhardware = $6 x 2 = $12

Notes:

* 1/2" SS tubing is expensive: McMaster-Carr (8989K891) = $160.
  Plus more bulkheads means a substantial expense

Vessels
=======

Hot Liquor Tank
---------------

Features:

* Use existing 10g cooler
* 120V heating element - 1500W
* Output w/ ball valve, QD
* Level gauge

### Prices ###

Total: $109

* Heating element
  * 1500W Element - Amazon = $20
  * Weldless electrical enclosure - brewhardware EWL1 = $24

* Output
  * Ball valve - brewhardware = $18
  * Bulkhead - brewhardware VB2 = $15
  * F-QD - brewhardware = $4

* Level gauge - brewhardware WLSLC = $28

Mash Tun
--------

Features:

* 15g (60qt)
* False bottom
* Output w/ ball valve, QD
* Dial temp probe
* No level gauge
* Instulated with Reflectix

### Prices ###

Total: $16

* 60qt pot - have
* false bottom - have
* output w/ ball valve, QD - have
* Dial temp probe - have
* Reflectix - Lowes = $16 (shared with boil kettle)

Boil Kettle
-----------

Features:

* 20g stainless kettle, 18" in diameter
* 5500W / 240V heating element (14.6" long)
* Output port w/ ball valve, QD
* Level gauge

### Prices ###

Total: $187

* Concord 80qt/20g - Amazon = $100 (only $10 more than 60qt)

* Heating element
  * 5500W element - have
  * Weldless electrical enclosure - brewhardware EWL1 = $24
  * Reflectix - (shared with mash tun)

* Output
  * Bulkhead - brewhardware = $14
  * Ball valve - brewhardware = $18
  * F-QD - brewhardware = $4

* Level gauge - brewhardware LP = $27
