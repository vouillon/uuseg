v1.0.0 2016-11-23 Zagreb
------------------------

- Unicode 9.0.0 support.
- OCaml standard library `Uchar.t` support.
  - Removes and substitutes `type Uuseg.uchar = int` by the (abstract)
    `Uchar.t` type. `Uchar.{of,to}_int` allows to recover the previous
    representation.
  - Removes the `Uuseg.is_uchar`. `Uchar.is_valid` can be used instead.
- Safe string support.
- Build depend on topkg.
- Relicense from BSD3 to ISC.

v0.9.0 2015-06-17 Cambridge (UK)
--------------------------------

- Support for Unicode 8.0.0's new line breaking and sentence boundary rules.
- `Uuseg.custom` add a unit argument.


v0.8.0 2014-12-23 Cugy (VD)
---------------------------

First release.
