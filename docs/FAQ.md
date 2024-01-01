**F.A.Q**

**Q. Is Archetype compatible with TAP?**

A. No, unfortunately the rail for TAP is simply too large to be easily accomodated on the existing carriage, and additionally, the toolhead is focused on rigidity optimisation as well as  other factors contributing to clean input shaper graphs, which in our experience is incompatible with TAP.

**Q. What machines is Archetype compatible with?**

A. Archetype is designed primarily for front rail MGN9 and MGN12 based printers, usually in the voron ecosystem such as the 2.4 or Trident, however it may be compatible with other gantry designs if they follow similar design restrictions and clerances.

**Q. How large and heavy is Archetype?**

A. Weight ranges depending on hotend and extruder choice, however the lower bounts are around 230g whilst the upper is around 350g, a breakneck setup with a DragonUHF+Spacer and a VZhex+breakneck block and all other associated hardware clocks in around 270g
All of the Archetypes currently retain full clerances on most stock machines, with some requiring flipped gantry with Y rails on top of the extrusion, but there should be no build volume losses. Archetype is dimensionally smaller than most toolheads, and the core is around the same size as Xol without the fans.

**Q. Why are the core screws angled?**

A. Angling the 4 main screws off of any major axis has some form factor advantages, but critically, it guarantees that the majority of fasteners are in compression, regardless of the direction of the print travel move. This, in combination with the added rigidity of having those fasteners throughout the skeleton of the toolhead significantly improve rigidity and overall strength.

**Q. Can i put Archetype on my Ender 3?**

A. No, and any attempts to do so will be met with unrelenting force.

**Q. Does Arcehtype work with stock voron frame and gantry parts?**

A. Yes, you should not require any major modifications to your voron printer, however there are a couple of caveats;
Front Idlers may have some clearance issues, so it is recommended to use lower profile idlers such as Ramalama idlers, or Clee's BFI. This should not be necessary with Breakneck
and if using Mjolnir or Atrocity along with stock plastic XY joints, you will need to move your Y rails to the top of the extrusion and "flip" your XY joints so the larger section is below. if using CNC XY joints, you do not need to flip anything.

**Q. What is the max supported temp for printing?**

A. As always, this will be heavily influenced by what material you print your toolhead in, but there should not be any significant deviations from normal use cases with normal plastics, ASA and ABS will likely top out at 75-80c chamber temps, PC blends are recommended for users printing at chamber temps above 70c or so, however experiement at your own discretion and use your own experience.
The fans that are present on the toolhead based fan archetypes are usually specced for Delta fans, as they have been shown to be more reliable in higher chamber temps, however check rated temps on datasheets, and use your own discretion. Fans will eventually die in a high temp chamber.
it is currently unknown what the longevity of 7040 fans in extrememly high temp machines is like, but they appear to be surviving in chambers with temps that top out at 80, further testing is needed for higher temps.
With all of this said, Archetype has been developed with High Temp in mind during its design, and where possible, consideration has been made to optimise it for those use cases with the improvements usually applying to all users.

**Q. What materials has Archetype been printed in?**

A. As above, it has been thoroughly tested with ASA and ABS, and there have been a good number of users printing in other exotic materials such as PCCF, PEKK, and even some PLA prototypes.
