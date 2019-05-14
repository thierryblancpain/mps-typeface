# Parsons MPS website typeface
This is the typeface for the Parsons MPS program website.

## Concept
When designing the program website, we wanted the concept and design to reflect principles that are innate to interactive media.

For example, typography in this context can change randomly (as on the website), or through continuous improvement (as new people contribute).

Therefore, we set out to design a display typeface that would reflect the values of change, evolution, expression, etc. rather than a ‘perfect’ finished end-state.

## License and Distribution
We decided to open the typeface to contributions in the hopes that students in the MPS program (and others) would add to, edit, and thereby improve the typeface as the program also evolves. New versions can be incorporated into the website or used for other projects.

To contribute, branch and edit the Glyphs file, and submit a pull request.

## Usage
Because of the project parameters and intention, this typeface is not complete (meaning there are a lot of missing glyphs, only basic spacing, etc.). It was designed to complement, dynamically, a ‘real’ typeface by using JavaScript to swap out randomized glyphs. So, to use this typeface, you will need to:
1. pair it with another typeface
2. write a program that can replace glyphs with glyphs from the MPS typeface

There are two sub-families in the Glyphs file:
- Pixel
- Expressive

Exporting from Glyphs.app:
1. Open `MPS-Sans.glyphs` on Glyphs
2. Modify the typeface as you need. First master must not be modify, second is for Expressive font and third is for Pixel.
3. Export the fonts with `⌘ + E` > Webfonts.
4. Select `Truetype`, `Automatic Hinting` and export in WOFF and WOFF2 directly in the `assets > fonts` folder of the website. Expressive and Pixel fonts will be exported.

