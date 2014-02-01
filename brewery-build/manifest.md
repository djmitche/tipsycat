Tools
=====

Requirements:

* 1.25" hole in BK for heating element
* Sight glass holes?
* Output holes?
* Element wrench
* Labeler
* Extra 10ga stranded wire, R/B/W/G, T90/THHN
* Extra 12ga stranded wire, R/B/W/G, T90/THHN
* LV 18..20ga wire, colors
* 10ga ring terminals
* 12ga spade terminals

### Prices ###

* SS Punch for 1.5" hole - TODO
* Step bits - TODO

Controller / Electric
=====================

This initial version is a very basic, almost entirely manual controller.
It needs to be able to control the various electrical components with switches, and little more.

I have two distinct circuits - one 240V/30A supply for heating, and one 120V/20A for pumps and other bits.
These will be wired entirely separately in this phase.

Pump Control
------------

This is a simple 3-gang outlet box with two 20A switches connected to the two halves of the center receptacle.
Power comes from a regular grounded NEMA 5-20P.
The upstream supply is GFCI-protected.

### Prices ###

* 3-gang outdoor box + fittings - ??
* 20A outlet - Lowes = $4
* 2x 20A switch - Lowes = $6x2 = $12
* Faceplate - Lowes = $3
* 8' 12-3 SJOOW - amazon = $7 (partial from 25')
* 8' 1/2" expandable sleeving - Amazon = $5 (partial from 25')
* 2x 3/8" x 4" heat-shrink - Amazon = $5
* L5-20P Plug - Amazon = $8

Option: 15A components with 15A fuse inline

Element Control
---------------

A three-way switch controls which of the two elements is active: the brew kettle (5500W / 240V) or the hot liquor tank (1500W / 120V), with the middle position not connected.
This switch drives contactors suitable for the high current to the elements.
The HLT hot lead also has an SSR in series with the contactor, connected to an STC-1000 temperature controller.

### Prices ###

* 4-space Main Lug Load Center - Lowes = $20
* 10A DIN-mount Breaker - oscsys = $5
* 25A SSR - Amazon = $12 w/ sink
* SSR Heat Sink - included
* 12VDC supply - have
* STC-1000 temp controller - have
* 2P 63a DIN-mount contactor - oscsys = $25
* 1P 25A DIN-mount contactor (extra pole unused) - oscsys = $16
* 8' 10-4 SJOOW - Amazon = $18
* 8' 1/2" expandable sleeving - Amazon = $5 (partial from 25')
* 3/4" x 4" heat-shrink 2pk - Amazon = $5
* 3-way 5A switch - OSCSYS = $6 (SKU176014); ebrewsupply = $4.50
* DIN Rail - oscsys = $4 (12")
* 1/2" cable clamps
* L14-30R compatible with load center
* L5-20R compatible with load center

Option: project board + break out receptacles into boxes

Vessel Connections
------------------

### Prices ###

* Brew Kettle Connection
  * L14-30P Plug - Amazon = $8
  * 8' 10-3 (H/N/G) flexible cord (SJOOW) - Home Depot = $16 (per foot)
  * 8' 1/2" expandable sleeving - Amazon = $5 (partial from 25')
  * 3/4" x 4" heat-shrink 2pk - Amazon = $5

* HLT Connection
  * L5-20P Plug - Amazon = $8
  * 8' 12-3 SJOOW - amazon = $7 (partial from 25')
  * 8' 1/2" expandable sleeving - Amazon = $5 (partial from 25')
    * might want 1/4"
  * 3/4" x 4" heat-shrink 2pk - Amazon = $5
    * might want 3/8"

Stand
=====

This is assembled as follows, to allow gravity feeding from HLT to MT:

      HLT
    +-----+
    |     |  MT    BK
    +-----+-----+-----+
    |     |P   P|     |
    +-----+-----+-----+

With the lower tier about 2.5' tall and the upper about 4.5' tall.
This system can easily accomodate the uneven floor in my basement.

* Joints: 2x4 Basics shelving system
* Verticals: 4 5' lengths, 4 3' lengths of 2x4
* Horizontals: 4 6' lengths, 14 2' lengths of 2x4

### Prices ###

Total: $105

* Joints - Lowes = $20 x 2 = $40
* Eleven 8' 2x4's - Lowes = $4x11 = $44

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

* Pump - amazon = $160; ryan = $135 (agreed)
* Ball valve - brewhardware = $18; ryan = free w/ pump
* 2x F-QD - $4 x 2 = $8

Hang-on Filler
--------------

Hangs over the side of a vessel to inject water from above.
For mashing, need one to recirculate hot liquor and one to recirculate wort.
For transferring, need one for boil keettle.

### Prices ###

Total: $28 x 2 = $56

* F-QD (MPT) - brewhardware = $4
* Platic Loc-Line (MPT) - brewhardware = $20
* 1/2" NPT coupling (FPT) - bargainfittings = $4

Notes:

* Existing fermenter filler has an F-QD and hose barb adapter
* Could use one with Loc-Line and one with 18" silicone tubing, just adding an elbow

HERMS Tube
----------

The first attempt is to use the existing copper wort chiller.
The existing thermoplastic hose will be adapted with female QD's to attach to a pump and the filler.

### Prices ###

Total = $40

* Copper coil, 3/8" OD 1/4" ID(?) - have
* Hand Clamp - amazon = $7
* Cutting board to brace against clamp - amazon = $7 (http://www.amazon.com/Stanton-Trading-2-Inch-Cutting-Board/dp/B0032AM0M6/ref=sr_1_31?s=kitchen&ie=UTF8&qid=1390750336&sr=1-31&keywords=cutting+board)
* 3/8" hose - 3/8" MPT - ebay = $3 x 2 = $6
* 3/8" FPT to 1/2" MPT bushing - brewhardware = $4 x 2 = $8
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

Total: $119

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

Total: $0

* 60qt pot - have
* false bottom - have
* output w/ ball valve, QD - have
* Dial temp probe - have
* Reflectix - shared with boil kettle

Boil Kettle
-----------

Features:

* 20g stainless kettle, 18" in diameter
* 5500W / 240V heating element (14.6" long)
* Output port w/ ball valve, QD
* Level gauge

### Prices ###

Total: $212

* Concord 80qt/20g - amazon = $100 (only $10 more than 60qt)

* Heating element
  * 5500W element - have
  * Weldless electrical enclosure - brewhardware EWL1 = $24
  * Reflectix - $25 (shared with mash tun)

* Output
  * Bulkhead - brewhardware = $14
  * Ball valve - brewhardware = $18
  * F-QD - brewhardware = $4

* Level gauge - brewhardware LP = $27
