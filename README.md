# embrdr
-----------------
A free, open-source software application fro the development of machine embroidery files.

Current version provides support for EXP or DST file  formats.


__________________________________

### Reference:
 http://www.achatina.de/sewing/main/TECHNICL.HTM

1.  EXP Format:

| address | Hex value | Explanation | Notes |
| :---- | :---- | :---- | :---: |
| NNNN | 00 7F NN NN | x+0   y+127 |
| NNNN | 7F 00 NN NN | x+127   y+0 |
| NNNN | 80 02 7F 00 | x+127   y+0 | Jump stitch, 25.4 mm |
| next | 7F 00 NN NN | x+127   y+0 |
| NNNN | 80 01 00 81 | x+0   y-127 | Color Change |



Copyright © 2018 Brendan Reddy-Best

Distributed under the Eclipse Public License either version 1.0 or (at
your option) any later version.
