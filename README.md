Nyquist v1 Case
===============

Here's case design files for the [Nyquist](https://keeb.io/collections/nyquist-parts) v1. It's a sandwich-style case with cutouts at the back to accomodate the USB jack and the TRRS jack.

There are two different designs included in this repository, one case with 9 screw holes around the exterior of the plate (`exterior-screws` directory), and one with 4 screw holes on the interior of the plate (i.e. all but one screw is hidden from view) (`interior-screws` directory).

Exterior case pieces
--------------------
The design file for the exterior screw case has 2 top, 2 bottom, and 8 middle layer pieces. This is good for 1 complete case for 2 halves.

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

There is also an alternative middle layer file (`middle-layer-tent.svg`) that has 3 holes on the sides of it to allow for testing using 3 screws. **Note:** This tenting design needs to be reworked, as with all 3 screws in, it's somewhat unstable, but is fine with 2 screws on the one side.

Interior case pieces
--------------------

There's only 2 different types of pieces the case uses:

- Top/Switch layer - Each half uses 1 of these
    - There are 2 different versions
    - `switch-layer-1u.svg` - All 1u keys
    - `switch-layer-universal.svg` - Supports both 1u and 2u configuration
- Bottom layer (`bottom-layer.svg`) - Each half uses 1 of these

Screws and Standoffs
--------------------
This case was designed to use M2 screws and standoffs. The holes in the middle layers are for the standoffs, while the holes in the top and bottom layers are only wide enough for the screws. M2 screws and standoffs that fit the case can be purchased at Keebio: [M2 Screws & Standoffs](https://keeb.io/products/m2-screws-and-standoffs)

Ponoko
------

### Arranging the Ponoko design yourself
To have the case made with Ponoko, you can't take the .svg files as is and send them off to them. First, you'll need to download the templates for P1, P2, & P3 sheets from here, depending on what vector editor you are using:

- [Inkscape templates](https://www.ponoko.com/starter-kits/inkscape)
- [Adobe Illustrator template](https://www.ponoko.com/starter-kits/adobe-illustrator)
- [Other](https://www.ponoko.com/make-and-sell/design-it-yourself)

### Pre-made Ponoko designs
There are a couple of files included that are ready to be sent off to Ponoko:

- P2-nyquist-v1-ponoko.eps
    - Complete case for both halves
    - You only need to make one of these on a P2 sheet
- P1-nyquist-middle.eps
    - 2 middle layer pieces
    - If doing 3mm (0.118 in) thickness, you'll need 3 or 4 P1 sheets to get to 9mm or 12mm of total thickness respectively
    - If doing 4mm (0.177 in) thickness, you'll need 2 P1 sheets to get to 9mm thickness

## Middle Layer Thickness
If you're having the middle layers made, from the top of the switch plate to the top of the bottom plate, the minimium distance between the two required is 12mm if the plastic on the header pins is removed. The requirement is slightly more (about 13.5mm) if you leave the plastic on. Therefore, the following middle layer thickness are needed based on the thickness of the switch layer:

- 1.5mm Stainless steel switch plate: 10.5mm
    - Usually accomplished with:
        - 2x4.5mm + 1x1.5mm layers
        - or 3x3mm + 1x1.5mm layers
        - or 3x4mm layers
- 3mm acrylic switch plate: 9mm
    - Usually accomplished with:
        - 2x4.5mm layers
        - or 3x3mm layers

License
-------
These case files are released under the MIT License.
