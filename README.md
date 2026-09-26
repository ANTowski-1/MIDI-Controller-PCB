# MIDI-Controller-PCB

REV: 1 — Known problems:
    Encoder A/B pins are connected to MCP23017, which makes them unusable, so mannual connection to free ESP GPIO pins is needed,
    Leds near Mute Buttons, aren't working corrctly, as they light up very dim becouse of capabilites of MCP23017 (digital representation is working on screen),
    Some of silkscreen markings are not correct (Pin description for display header)
    
Before building using 1st revision think it through, but if you are intrested in 2nd revision, it will propably be done in the end of the year, based on intrest, so create an issue or write to me directly to let me know about your intrest!

This Repo contains KiCad projects of MIDI-Controller PCB.
Whole documentation can be found in separate repo: ANTowski-1/MIDI-Controller.
(As of end of September 2026, documentations is not made as for code still being developed)

This is an Hobbyst-made project, that isn't connected with MIDI Association in any way, apart from utilising the MIDI 2.0 standard.
