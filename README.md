# Hybrid Base Music Notes

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

The table below shows HBMN in comparison to other systems.

| HBMN | Name | MIDI |
| ---- | ---- | ---- |
|  57  |      | 127  |
|  56  |      | 126  |
|  55  |      | 125  |
|  54  |      | 124  |
|  53  |      | 123  |
|  52  |      | 122  |
|  51  |      | 121  |
|  50  |      | 120  |
|  4b  |      | 119  |
|  4a  |      | 118  |
|  49  |      | 117  |
|  48  |      | 116  |
|  47  |      | 115  |
|  46  |      | 114  |
|  45  |      | 113  |
|  44  |      | 112  |
|  43  |      | 111  |
|  42  |      | 110  |
|  41  |      | 109  |
|  40  |      | 108  |
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
