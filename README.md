Copyright (C) 2020- mirage335
See the end of the file for license conditions.
See license.txt for flightDeck license conditions.

flightDeck

Despite the name, more of a general purpose 'office chair' with accessories for intensive 'desk work' and VR. Assumes a fairly typical 'driver's seat' power chair.


# Usage


# Distribution

Consider providing end-users an entire copy of this repository with all submodules, in addition to PDF documents. Physical USB flash devices may be suitable for the repository, printed hardcopy may be suitable for the PDF documents.


# Design

WARNING: Units are mixed. Some sketches and other dimensions use inches, some use metric. This is due to the combination of commodity lumber de-facto standards with designs for metric components.


Chair is illustrated only roughly. Seat length includes leg extension fully extended.

Bolt hole positions for chair and such are NOT modeled in CAD. Only important landmarks are modeled.


# Redistribution and Preservation

Entire 'recursive' clones of this repository with all submodules may be appropriate for redistribution and preservation.


# Safety

DANGER: Powered chairs have moving machinery and other components designed for automotive use. Pinch points or other hazards may be present.


# FutureWork


# Reference


# Directory Specification

Consider keeping a copy of this specification alongside relevant projects for reference.

Please regard as a loose specification intended to offer unallocated regions for expansion and subordinate to any improvements that may be found in actual implementations.


Projects which may be assembled into larger projects, if sufficiently well-developed, should include their own appropriate directories, rather than referencing files shared within larger projects. That is to say, a sort of 'static linking' approach is strongly recommended.



Numbered directories with '[z]-' in their prefix and a '/' may substitute the '/' for either a '-' or separate directories.

Numbered directories of top-directories may be placed alongside top-directories if desired. Numbering scheme is intended to minimize conflicts.

Templates should populate only the most usual directories. Not all directories need be populated for a project.


```

_lib	- software, records, etc, typically uniquely needed by specific CAD model

00[00]-RESERVED (do NOT use)


01[00]-Bundle
	0110-Frames
	0150-Actuators
	0151[z]-Thruster/Driver
		Components only used for these?
		Screws used within these?
	0160-Tools
		Nozzle
		Hot-End
		Cold-End
		Extension (Bowden Tube)
	0162-Supplementary
		Filament Storage
	0165-Slab (workpiece mounting surface)
	0170-Tray (surface to mount electronics and similar)
	0172-Rack (enclosure for electronics and similar, and/or junction box)
	0175-Cabinet (arbitrary storage)



11[00]-Structural (Passive, Cut To Size)
	1110[z]-Extrusions/Timbers
		_resized
	1112[z]-Sheets/Panels/Plates (for frames only)
		_rescaled (PreDrilled only)
	1115-Backing (Table)



30[00]-Conveyance
	3030[z]-Shaft/Piston
	3032-LeadScrew
	3033[z]-Belts
	3035- to 3038- RESERVED (do NOT use)

35[00]-Couplings (including flexible, u-joints, etc)
	3530-LeadScrew_to_Motor



50[00]-Effectors
	5050[z]-Motors/Steppers/Servos
	5051[z]-RotaryBearings/RotaryShims
	
	5052[z]-NutBlocks/PlatesEffectors/BracketsEffectors (typically belt tie-down points), etc.
	5053-RESERVED
	
	5054[z]-Guides (Wheels/Bushings/LinearBearings)
	
	5055-Pulleys
	5056-Gears
	
	5058-Limit Switch

55[00]-RESERVED (do NOT use)
	

(6000 RESERVED)

(7000 RESERVED)



80[00]-Endpoints
	8080-Plug
		RJ45
		misc
	8081-Jack
		RJ45
		misc
	8082-RESERVED (do NOT use)
	8083-RESERVED (do NOT use)

85[00]-Dissipator
	8580-Fans
	8581-Pump
	8582-Heatsink
	8585-Radiator

9000-Miscellaneous
	9090z-Screws/Bolts
	9095-frequent (most frequently used)
	9099-Misc
		zMisc (unsortred, typically uniquely needed by specific CAD model)

9100-KEEPOUT (solid objects used to mark regions reserved for future use)

94[00]
to
98[00]
	RESERVED for future use

99[00]-import
	RESERVED for future use


```



# Third-Party Copyright Notices

Third-Party copyrights are noted within text files alongside directories containing the original files, and/or within text files alongside directories containing the modified files, and/or within version control commit history.

Some copyright licenses have specific requirements, and some authors have specific requests, to prominently display copyright notices - these are included here.

However, the manner some or all of these third-party files are used may in fact be fair use, in which case the third-party licenses would not in fact have any effect on the license requirements for the otherwise possibly derivative project.


"
This design incorporates OpenBuilds, LLC design work(s) shared Open Source under the CC BY-SA 4.0 License.
"
... or this design may incorporate OpenBuilds, LLC design work(s)...







# Copyright

This file is part of flightDeck.

flightDeck is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

flightDeck is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with flightDeck.  If not, see <http://www.gnu.org/licenses/>.








