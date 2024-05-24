# Hybrid-Base Music Notes

Hybrid-Base Music Notes is a system for writing musical notes. It can be adapted to any scale which divides octaves equally.

The rightmost digit is in the number-base equal to the number of divisions in the octave. This digit is used to
represent the note. E.g. If we wish to represent western music in 12-note equal temperament, base-12 would be used. For a pentatonic scale, base-5 would
be used.

All other digits left of the rightmost digit are in base-10.
These digits are used to represent the number of octaves
from the base octave.

00 is the base note. It is the first note of the octave deemed to be base octave. In western music, this could be
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
|  3b  | B7      | 107  | 87    |
|  3a  | A♯7/B♭7 | 106  | 86    |
|  39  | A7      | 105  | 85    |
|  38  | G♯7/A♭7 | 104  | 84    |
|  37  | G7      | 103  | 83    |
|  36  | F♯7/G♭7 | 102  | 82    |
|  35  | F7      | 101  | 81    |
|  34  | E7      | 100  | 80    |
|  33  | D♯7/E♭7 | 99   | 79    |
|  32  | D7      | 98   | 78    |
|  31  | C♯7/D♭7 | 97   | 77    |
|  30  | C7      | 96   | 76    |
|  2b  | B6      | 95   | 75    |
|  2a  | A♯6/B♭6 | 94   | 74    |
|  29  | A6      | 93   | 73    |
|  28  | G♯6/A♭6 | 92   | 72    |
|  27  | G6      | 91   | 71    |
|  26  | F♯6/G♭6 | 90   | 70    |
|  25  | F6      | 89   | 69    |
|  24  | E6      | 88   | 68    |
|  23  | D♯6/E♭6 | 87   | 67    |
|  22  | D6      | 86   | 66    |
|  21  | C♯6/D♭6 | 85   | 65    |
|  20  | C6      | 84   | 64    |
|  1b  | B5      | 83   | 63    |
|  1a  | A♯5/B♭5 | 82   | 62    |
|  19  | A5      | 81   | 61    |
|  18  | G♯5/A♭5 | 80   | 60    |
|  17  | G5      | 79   | 59    |
|  16  | F♯5/G♭5 | 78   | 58    |
|  15  | F5      | 77   | 57    |
|  14  | E5      | 76   | 56    |
|  13  | D♯5/E♭5 | 75   | 55    |
|  12  | D5      | 74   | 54    |
|  11  | C♯5/D♭5 | 73   | 53    |
|  10  | C5      | 72   | 52    |
|  0b  | B4      | 71   | 51    |
|  0a  | A♯4/B♭4 | 70   | 50    |
|  09  | A4      | 69   | 49    |
|  08  | G♯4/A♭4 | 68   | 48    |
|  07  | G4      | 67   | 47    |
|  06  | F♯4/G♭4 | 66   | 46    |
|  05  | F4      | 65   | 45    |
|  04  | E4      | 64   | 44    |
|  03  | D♯4/E♭4 | 63   | 43    |
|  02  | D4      | 62   | 42    |
|  01  | C♯4/D♭4 | 61   | 41    |
|  00  | C4      | 60   | 40    |
| -1b  | B3      | 59   | 39    |
| -1a  | A♯3/B♭3 | 58   | 38    |
| -19  | A3      | 57   | 37    |
| -18  | G♯3/A♭3 | 56   | 36    |
| -17  | G3      | 55   | 35    |
| -16  | F♯3/G♭3 | 54   | 34    |
| -15  | F3      | 53   | 33    |
| -14  | E3      | 52   | 32    |
| -13  | D♯3/E♭3 | 51   | 31    |
| -12  | D3      | 50   | 30    |
| -11  | C♯3/D♭3 | 49   | 29    |
| -10  | C3      | 48   | 28    |
| -2b  | B2      | 47   | 27    |
| -2a  | A♯2/B♭2 | 46   | 26    |
| -29  | A2      | 45   | 25    |
| -28  | G♯2/A♭2 | 44   | 24    |
| -27  | G2      | 43   | 23    |
| -26  | F♯2/G♭2 | 42   | 22    |
| -25  | F2      | 41   | 21    |
| -24  | E2      | 40   | 20    |
| -23  | D♯2/E♭2 | 39   | 19    |
| -22  | D2      | 38   | 18    |
| -21  | C♯2/D♭2 | 37   | 17    |
| -20  | C2      | 36   | 16    |
| -3b  | B1      | 35   | 15    |
| -3a  | A♯1/B♭1 | 34   | 14    |
| -39  | A1      | 33   | 13    |
| -38  | G♯1/A♭1 | 32   | 12    |
| -37  | G1      | 31   | 11    |
| -36  | F♯1/G♭1 | 30   | 10    |
| -35  | F1      | 29   | 9     |
| -34  | E1      | 28   | 8     |
| -33  | D♯1/E♭1 | 27   | 7     |
| -32  | D1      | 26   | 6     |
| -31  | C♯1/D♭1 | 25   | 5     |
| -30  | C1      | 24   | 4     |
| -4b  | B0      | 23   | 3     |
| -4a  | A♯0/B♭0 | 22   | 2     |
| -49  | A0      | 21   | 1     |
| -48  | G♯0/A♭0 | 20   |       |
| -47  | G0      | 19   |       |
| -46  | F♯0/G♭0 | 18   |       |
| -45  | F0      | 17   |       |
| -44  | E0      | 16   |       |
| -43  | D♯0/E♭0 | 15   |       |
| -42  | D0      | 14   |       |
| -41  | C♯0/D♭0 | 13   |       |
| -40  | C0      | 12   |       |
| -5b  |         | 11   |       |
| -5a  |         | 10   |       |
| -59  |         | 9    |       |
| -58  |         | 8    |       |
| -57  |         | 7    |       |
| -56  |         | 6    |       |
| -55  |         | 5    |       |
| -54  |         | 4    |       |
| -53  |         | 3    |       |
| -52  |         | 2    |       |
| -51  |         | 1    |       |
| -50  |         | 0    |       |
