# Hybrid-Base Music Notes

Hybrid Base Music Notes is a system for writing musical notes. It can be adapted to any scale which divides octaves equally.

The rightmost digit is in the number-base equal to the number of divisions in the octave. This digit is used to
represent the note name. E.g. If we wish to represent western music in 12-note equal temperament, base-12 would be used. For a pentatonic scale, base-5 would
be used.

All other digits left of the rightmost digit are in base-10.
These digits will be used to represent the number of octaves
from the base octave.

00 is the base note. It is the first note of the octave deemed to be center octave. In western music, this could be
middle C.

Counting backwards into the negatives is a bit special. The leftmost digits representing the octaves and count backwards as expected, but the rightmost digit representing the note keeps the same order as when counting upwards.

The table below shows HBMN in comparison to other values.

| HBMN | Name    | MIDI | Piano | Freq     |
| ---- | ------- | ---- | ----- | -------- |
|  57  | G9      | 127  |       | 12543.85 |
|  56  | F♯9/G♭9 | 126  |       | 11839.82 |
|  55  | F9      | 125  |       | 11175.30 |
|  54  | E9      | 124  |       | 10548.08 |
|  53  | D♯9/E♭9 | 123  |       |  9956.06 |
|  52  | D9      | 122  |       |  9397.27 |
|  51  | C♯9/D♭9 | 121  |       |  8869.84 |
|  50  | C9      | 120  |       |  8372.02 |
|  4b  | B8      | 119  |       |  7902.13 |
|  4a  | A♯8/B♭8 | 118  |       |  7458.62 |
|  49  | A8      | 117  |       |  7040.00 |
|  48  | G♯8/A♭8 | 116  |       |  6644.88 |
|  47  | G8      | 115  |       |  6271.93 |
|  46  | F♯8/G♭8 | 114  |       |  5919.91 |
|  45  | F8      | 113  |       |  5587.65 |
|  44  | E8      | 112  |       |  5274.04 |
|  43  | D♯8/E♭8 | 111  |       |  4978.03 |
|  42  | D8      | 110  |       |  4698.64 |
|  41  | C♯8/D♭8 | 109  |       |  4434.92 |
|  40  | C8      | 108  | 88    |  4186.01 |



|  3b  |      | 107  |
|  3a  |      | 106  |
|  39  |      | 105  |
|  38  |      | 104  |
|  37  |      | 103  |
|  36  |      | 102  |
|  35  |      | 101  |
|  34  |      | 100  |
|  33  |      | 99   |
|  32  |      | 98   |
|  31  |      | 97   |
|  30  |      | 96   |





|  2b  |      | 95   |
|  2a  |      | 94   |
|  29  |      | 93   |
|  28  |      | 92   |
|  27  |      | 91   |
|  26  |      | 90   |
|  25  |      | 89   |
|  24  |      | 88   |
|  23  |      | 87   |
|  22  |      | 86   |
|  21  |      | 85   |
|  20  |      | 84   |
|  1b  |      | 83   |
|  1a  |      | 82   |
|  19  |      | 81   |
|  18  |      | 80   |
|  17  |      | 79   |
|  16  |      | 78   |
|  15  |      | 77   |
|  14  |      | 76   |
|  13  |      | 75   |
|  12  |      | 74   |
|  11  |      | 73   |
|  10  |      | 72   |
|  0b  |      | 71   |
|  0a  |      | 70   |
|  09  |      | 69   |
|  08  |      | 68   |
|  07  |      | 67   |
|  06  |      | 66   |
|  05  |      | 65   |
|  04  |      | 64   |
|  03  |      | 63   |
|  02  |      | 62   |
|  01  |      | 61   |
|  00  |      | 60   |
| -1b  |      | 59   |
| -1a  |      | 58   |
| -19  |      | 57   |
| -18  |      | 56   |
| -17  |      | 55   |
| -16  |      | 54   |
| -15  |      | 53   |
| -14  |      | 52   |
| -13  |      | 51   |
| -12  |      | 50   |
| -11  |      | 49   |
| -10  |      | 48   |
| -2b  |      | 47   |
| -2a  |      | 46   |
| -29  |      | 45   |
| -28  |      | 44   |
| -27  |      | 43   |
| -26  |      | 42   |
| -25  |      | 41   |
| -24  |      | 40   |
| -23  |      | 39   |
| -22  |      | 38   |
| -21  |      | 37   |
| -20  |      | 36   |
| -3b  |      | 35   |
| -3a  |      | 34   |
| -39  |      | 33   |
| -38  |      | 32   |
| -37  |      | 31   |
| -36  |      | 30   |
| -35  |      | 29   |
| -34  |      | 28   |
| -33  |      | 27   |
| -32  |      | 26   |
| -31  |      | 25   |
| -30  |      | 24   |
| -4b  |      | 23   |
| -4a  |      | 22   |
| -49  |      | 21   |
| -48  |      | 20   |
| -47  |      | 19   |
| -46  |      | 18   |
| -45  |      | 17   |
| -44  |      | 16   |
| -43  |      | 15   |
| -42  |      | 14   |
| -41  |      | 13   |
| -40  |      | 12   |
| -5b  |      | 11   |
| -5a  |      | 10   |
| -59  |      | 9    |
| -58  |      | 8    |
| -57  |      | 7    |
| -56  |      | 6    |
| -55  |      | 5    |
| -54  |      | 4    |
| -53  |      | 3    |
| -52  |      | 2    |
| -51  |      | 1    |
| -50  |      | 0    |
