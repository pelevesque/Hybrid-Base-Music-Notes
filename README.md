# Hybrid Base Music Notes

Hybrid Base Music Notes is a system for writing musical notes.

The rightmost digit is in the number-base equal to the number of divisions in the octave. This digit is used to
represent the note name. E.g. If we wish to represent western music in 12-note equal temperament, base-12 would be used. For a pentatonic scale, base-5 would
be used.

All other digits left of the rightmost digit are in base-10.
These digits will be used to represent the number of octaves
from the base octave.

00 is the base note. It is the first note of the octave deemed to be center octave. In western music, this could be
middle C.

Counting backwards into the negatives is a bit special. The leftmost digits representing the octaves and count backwards as expected, but the rightmost digit representing the note keeps the same order as when counting upwards.

The table below shows HBMN in comparison to other systems.







