# Hybrid-Base Music Notes

## Birth

Hybrid-Base Music Notes was invented on May 23rd 2024.

Copyright 2024 Pierre-Emmanuel Lévesque

## About

Hybrid-Base Music Notes is a system for writing musical notes.

It is formed in two parts:

1)

A rightmost digit in the number-base equal to the number of
notes in the octave. This digit is used to represent the note.

E.g. A number-base of 12 is used to represent western music in
twelve notes. For a pentatonic scale, base-5 would be used.

Note: The number-base can change per octave if different octaves
of the scale have different number of notes. Its also possible to
use any element in the number-base system. A base-10 system could
use a b c d e f g h i j instead of 0 1 2 3 4 5 6 7 8 9.

2)



All other digits left of the rightmost digit are in base-10.
These digits are used to represent the number of octaves
from the base octave.















- give example... give series of notes...








-- Here we give examples:


----------------------------------------------------------------------


00 is the base note. It is the first note of the octave deemed to be base octave. In western music, this could be
middle C.

Counting backwards into the negatives is a bit special. The leftmost digits representing the octaves and count backwards as expected, but the rightmost digit representing the note keeps the same order as when counting upwards.

The table below shows HBMN in comparison to other values.

| HBMN | Name    | MIDI | Piano | Freq     |
| ---- | ------- | ---- | ----- | -------- |
|  97  | G9      | 127  |       | 12543.85 |
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
|  7b  | B7      | 107  | 87    |  3951.07 |
|  7a  | A♯7/B♭7 | 106  | 86    |  3729.31 |
|  79  | A7      | 105  | 85    |  3520.00 |
|  78  | G♯7/A♭7 | 104  | 84    |  3322.44 |
|  77  | G7      | 103  | 83    |  3135.96 |
|  76  | F♯7/G♭7 | 102  | 82    |  2959.96 |
|  75  | F7      | 101  | 81    |  2793.83 |
|  74  | E7      | 100  | 80    |  2637.02 |
|  73  | D♯7/E♭7 | 99   | 79    |  2489.02 |
|  72  | D7      | 98   | 78    |  2349.32 |
|  71  | C♯7/D♭7 | 97   | 77    |  2217.46 |
|  70  | C7      | 96   | 76    |  2093.00 |
|  6b  | B6      | 95   | 75    |  1975.53 |
|  6a  | A♯6/B♭6 | 94   | 74    |  1864.66 |
|  69  | A6      | 93   | 73    |  1760.00 |
|  68  | G♯6/A♭6 | 92   | 72    |  1661.22 |
|  67  | G6      | 91   | 71    |  1567.98 |
|  66  | F♯6/G♭6 | 90   | 70    |  1479.98 |
|  65  | F6      | 89   | 69    |  1396.91 |
|  64  | E6      | 88   | 68    |  1318.51 |
|  63  | D♯6/E♭6 | 87   | 67    |  1244.51 |
|  62  | D6      | 86   | 66    |  1174.66 |
|  61  | C♯6/D♭6 | 85   | 65    |  1108.73 |
|  60  | C6      | 84   | 64    |  1046.50 |
|  5b  | B5      | 83   | 63    |   987.77 |
|  5a  | A♯5/B♭5 | 82   | 62    |   932.33 |
|  59  | A5      | 81   | 61    |   880.00 |
|  58  | G♯5/A♭5 | 80   | 60    |   830.61 |
|  57  | G5      | 79   | 59    |   783.99 |
|  56  | F♯5/G♭5 | 78   | 58    |   739.99 |
|  55  | F5      | 77   | 57    |   698.46 |
|  54  | E5      | 76   | 56    |   659.26 |
|  53  | D♯5/E♭5 | 75   | 55    |   622.25 |
|  52  | D5      | 74   | 54    |   587.33 |
|  51  | C♯5/D♭5 | 73   | 53    |   554.37 |
|  50  | C5      | 72   | 52    |   523.25 |
|  4b  | B4      | 71   | 51    |   493.88 |
|  4a  | A♯4/B♭4 | 70   | 50    |   466.16 |
|  49  | A4      | 69   | 49    |   440.00 |
|  48  | G♯4/A♭4 | 68   | 48    |   415.30 |
|  47  | G4      | 67   | 47    |   392.00 |
|  46  | F♯4/G♭4 | 66   | 46    |   369.99 |
|  45  | F4      | 65   | 45    |   349.23 |
|  44  | E4      | 64   | 44    |   329.63 |
|  43  | D♯4/E♭4 | 63   | 43    |   311.13 |
|  42  | D4      | 62   | 42    |   293.66 |
|  41  | C♯4/D♭4 | 61   | 41    |   277.18 |
|  40  | C4      | 60   | 40    |   261.63 |
|  3b  | B3      | 59   | 39    |   246.94 |
|  3a  | A♯3/B♭3 | 58   | 38    |   233.08 |
|  39  | A3      | 57   | 37    |   220.00 |
|  38  | G♯3/A♭3 | 56   | 36    |   207.65 |
|  37  | G3      | 55   | 35    |   196.00 |
|  36  | F♯3/G♭3 | 54   | 34    |   185.00 |
|  35  | F3      | 53   | 33    |   174.61 |
|  34  | E3      | 52   | 32    |   164.81 |
|  33  | D♯3/E♭3 | 51   | 31    |   155.56 |
|  32  | D3      | 50   | 30    |   146.83 |
|  31  | C♯3/D♭3 | 49   | 29    |   138.59 |
|  30  | C3      | 48   | 28    |   130.81 |
|  2b  | B2      | 47   | 27    |   123.47 |
|  2a  | A♯2/B♭2 | 46   | 26    |   116.54 |
|  29  | A2      | 45   | 25    |   110.00 |
|  28  | G♯2/A♭2 | 44   | 24    |   103.83 |
|  27  | G2      | 43   | 23    |    98.00 |
|  26  | F♯2/G♭2 | 42   | 22    |    92.50 |
|  25  | F2      | 41   | 21    |    87.31 |
|  24  | E2      | 40   | 20    |    82.41 |
|  23  | D♯2/E♭2 | 39   | 19    |    77.78 |
|  22  | D2      | 38   | 18    |    73.42 |
|  21  | C♯2/D♭2 | 37   | 17    |    69.30 |
|  20  | C2      | 36   | 16    |    65.41 |
|  1b  | B1      | 35   | 15    |    61.74 |
|  1a  | A♯1/B♭1 | 34   | 14    |    58.27 |
|  19  | A1      | 33   | 13    |    55.00 |
|  18  | G♯1/A♭1 | 32   | 12    |    51.91 |
|  17  | G1      | 31   | 11    |    49.00 |
|  16  | F♯1/G♭1 | 30   | 10    |    46.25 |
|  15  | F1      | 29   | 9     |    43.65 |
|  14  | E1      | 28   | 8     |    41.20 |
|  13  | D♯1/E♭1 | 27   | 7     |    38.89 |
|  12  | D1      | 26   | 6     |    36.71 |
|  11  | C♯1/D♭1 | 25   | 5     |    34.65 |
|  10  | C1      | 24   | 4     |    32.70 |
|  0b  | B0      | 23   | 3     |    30.87 |
|  0a  | A♯0/B♭0 | 22   | 2     |    29.14 |
|  09  | A0      | 21   | 1     |    27.50 |
|  08  | G♯0/A♭0 | 20   |       |    25.96 |
|  07  | G0      | 19   |       |    24.50 |
|  06  | F♯0/G♭0 | 18   |       |    23.12 |
|  05  | F0      | 17   |       |    21.83 |
|  04  | E0      | 16   |       |    20.60 |
|  03  | D♯0/E♭0 | 15   |       |    19.45 |
|  02  | D0      | 14   |       |    18.35 |
|  01  | C♯0/D♭0 | 13   |       |    17.32 |
|  00  | C0      | 12   |       |    16.35 |
| -1b  |         | 11   |       |    15.43 |
| -1a  |         | 10   |       |    14.57 |
| -19  |         | 9    |       |    13.75 |
| -18  |         | 8    |       |    12.98 |
| -17  |         | 7    |       |    12.25 |
| -16  |         | 6    |       |    11.56 |
| -15  |         | 5    |       |    10.91 |
| -14  |         | 4    |       |    10.30 |
| -13  |         | 3    |       |     9.72 |
| -12  |         | 2    |       |     9.18 |
| -11  |         | 1    |       |     8.66 |
| -10  |         | 0    |       |     8.18 |
