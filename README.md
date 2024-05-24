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
|  97  | G9    | 127  |       | 12543.85 |
|  96  | F♯9/G♭9 | 126  |       | 11839.82 |
|  95  | F9      | 125  |       | 11175.30 |
|  94  | E9      | 124  |       | 10548.08 |
|  93  | D♯9/E♭9 | 123  |       |  9956.06 |
|  92  | D9      | 122  |       |  9397.27 |
|  91  | C♯9/D♭9 | 121  |       |  8869.84 |
|  90  | C9      | 120  |       |  8372.02 |
|  8b  | B8      | 119  |       |  7902.13 |
|  8a  | A♯8/B♭8 | 118  |       |  7458.62 |
|  89  | A8      | 117  |       |  7040.00 |
|  88  | G♯8/A♭8 | 116  |       |  6644.88 |
|  87  | G8      | 115  |       |  6271.93 |
|  86  | F♯8/G♭8 | 114  |       |  5919.91 |
|  85  | F8      | 113  |       |  5587.65 |
|  84  | E8      | 112  |       |  5274.04 |
|  83  | D♯8/E♭8 | 111  |       |  4978.03 |
|  82  | D8      | 110  |       |  4698.64 |
|  81  | C♯8/D♭8 | 109  |       |  4434.92 |
|  80  | C8      | 108  | 88    |  4186.01 |
|  7b  | B7      | 107  | 87    |
|  7a  | A♯7/B♭7 | 106  | 86    |
|  79  | A7      | 105  | 85    |
|  78  | G♯7/A♭7 | 104  | 84    |
|  77  | G7      | 103  | 83    |
|  76  | F♯7/G♭7 | 102  | 82    |
|  75  | F7      | 101  | 81    |
|  74  | E7      | 100  | 80    |
|  73  | D♯7/E♭7 | 99   | 79    |
|  72  | D7      | 98   | 78    |
|  71  | C♯7/D♭7 | 97   | 77    |
|  70  | C7      | 96   | 76    |
|  6b  | B6      | 95   | 75    |
|  6a  | A♯6/B♭6 | 94   | 74    |
|  69  | A6      | 93   | 73    |
|  68  | G♯6/A♭6 | 92   | 72    |
|  67  | G6      | 91   | 71    |
|  66  | F♯6/G♭6 | 90   | 70    |
|  65  | F6      | 89   | 69    |
|  64  | E6      | 88   | 68    |
|  63  | D♯6/E♭6 | 87   | 67    |
|  62  | D6      | 86   | 66    |
|  61  | C♯6/D♭6 | 85   | 65    |
|  60  | C6      | 84   | 64    |
|  5b  | B5      | 83   | 63    |
|  5a  | A♯5/B♭5 | 82   | 62    |
|  59  | A5      | 81   | 61    |
|  58  | G♯5/A♭5 | 80   | 60    |
|  57  | G5      | 79   | 59    |
|  56  | F♯5/G♭5 | 78   | 58    |
|  55  | F5      | 77   | 57    |
|  54  | E5      | 76   | 56    |
|  53  | D♯5/E♭5 | 75   | 55    |
|  52  | D5      | 74   | 54    |
|  51  | C♯5/D♭5 | 73   | 53    |
|  50  | C5      | 72   | 52    |
|  4b  | B4      | 71   | 51    |
|  4a  | A♯4/B♭4 | 70   | 50    |
|  49  | A4      | 69   | 49    |
|  48  | G♯4/A♭4 | 68   | 48    |
|  47  | G4      | 67   | 47    |
|  46  | F♯4/G♭4 | 66   | 46    |
|  45  | F4      | 65   | 45    |
|  44  | E4      | 64   | 44    |
|  43  | D♯4/E♭4 | 63   | 43    |
|  42  | D4      | 62   | 42    |
|  41  | C♯4/D♭4 | 61   | 41    |
|  40  | C4      | 60   | 40    |
|  3b  | B3      | 59   | 39    |
|  3a  | A♯3/B♭3 | 58   | 38    |
|  39  | A3      | 57   | 37    |
|  38  | G♯3/A♭3 | 56   | 36    |
|  37  | G3      | 55   | 35    |
|  36  | F♯3/G♭3 | 54   | 34    |
|  35  | F3      | 53   | 33    |
|  34  | E3      | 52   | 32    |
|  33  | D♯3/E♭3 | 51   | 31    |
|  32  | D3      | 50   | 30    |
|  31  | C♯3/D♭3 | 49   | 29    |
|  30  | C3      | 48   | 28    |
|  2b  | B2      | 47   | 27    |
|  2a  | A♯2/B♭2 | 46   | 26    |
|  29  | A2      | 45   | 25    |
|  28  | G♯2/A♭2 | 44   | 24    |
|  27  | G2      | 43   | 23    |
|  26  | F♯2/G♭2 | 42   | 22    |
|  25  | F2      | 41   | 21    |
|  24  | E2      | 40   | 20    |
|  23  | D♯2/E♭2 | 39   | 19    |
|  22  | D2      | 38   | 18    |
|  21  | C♯2/D♭2 | 37   | 17    |
|  20  | C2      | 36   | 16    |
|  1b  | B1      | 35   | 15    |
|  1a  | A♯1/B♭1 | 34   | 14    |
|  19  | A1      | 33   | 13    |
|  18  | G♯1/A♭1 | 32   | 12    |
|  17  | G1      | 31   | 11    |
|  16  | F♯1/G♭1 | 30   | 10    |
|  15  | F1      | 29   | 9     |
|  14  | E1      | 28   | 8     |
|  13  | D♯1/E♭1 | 27   | 7     |
|  12  | D1      | 26   | 6     |
|  11  | C♯1/D♭1 | 25   | 5     |
|  10  | C1      | 24   | 4     |
|  0b  | B0      | 23   | 3     |
|  0a  | A♯0/B♭0 | 22   | 2     |
|  09  | A0      | 21   | 1     |
|  08  | G♯0/A♭0 | 20   |       |
|  07  | G0      | 19   |       |
|  06  | F♯0/G♭0 | 18   |       |
|  05  | F0      | 17   |       |
|  04  | E0      | 16   |       |
|  03  | D♯0/E♭0 | 15   |       |
|  02  | D0      | 14   |       |
|  01  | C♯0/D♭0 | 13   |       |
|  00  | C0      | 12   |       |
| -1b  |         | 11   |       |
| -1a  |         | 10   |       |
| -19  |         | 9    |       |
| -18  |         | 8    |       |
| -17  |         | 7    |       |
| -16  |         | 6    |       |
| -15  |         | 5    |       |
| -14  |         | 4    |       |
| -13  |         | 3    |       |
| -12  |         | 2    |       |
| -11  |         | 1    |       |
| -10  |         | 0    |       |
