Nyquist v1 Case
===============

Here's case design files for the Nyquist v1. It's a sandwich-style case with cutouts at the back to accomodate the USB jack and the TRRS jack.

The design file has 2 top, 2 bottom, and 8 middle layer pieces. This is good for 1 complete case for 2 halves.

Pieces
------
There's 4 different types of pieces the case uses:

- Top/Switch layer - Each half uses 1 of these
    - There are 3 different versions
    - `switch-layer-1u.svg` - All 1u keys
    - `switch-layer-2u.svg` - 2u key at lower right (or lower left if plate is flipped for other half)
    - `switch-layer-universal.svg` - Supports both 1u and 2u configuration
- Bottom layer (`bottom-layer.svg`) - Each half uses 1 of these
- Middle layer (`middle-layer.svg`)
    - C-shaped piece - Each half uses 3 of these, use a 4th one if you need more space (like when using a Pro Micro with Mini USB jack)
    - Stick piece - Same number as the C-Shaped piece

There is also an alternative middle layer file (`middle-layer-tent.svg`) that has 3 holes on the sides of it to allow for testing using 3 screws.

Screws and Standoffs
--------------------
This case was designed to use M2 screws and standoffs. The holes in the middle layers are for the standoffs, while the holes in the top and bottom layers are only wide enough for the screws.

Ponoko
------
The .eps file is designed for use with a Ponoko P2 sheet. A 3mm or 4.5mm sheet is recommended if using acrylic. The kerf of all the files (.eps and .svg) was set to 0.15mm when designed.

License
-------
These case files are released under the MIT License.
