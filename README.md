# KI Beamer Template

A beamer template inspired by Karolinska Institutet. The template is consistent with the Karolinska Institutet graphic identity guidelines, see [here](https://internwebben.ki.se/en/graphic-rules) for more information.

## Requirements

1. `xelatex` to use custom fonts;
2. [These](https://www.google.com/fonts#UsePlace:use/Collection:Droid+Sans:400,700|Droid+Sans+Mono|Droid+Serif:400,400italic,700,700italic) fonts.

## Usage

1. Download both the theme file `beamerthemeKI.sty` and logo `ki-logo_vert_neg_1.pdf`, and place them in the same folder of your `.tex` file;
2. Add `\usetheme{KI}` in your preamble;
3. Compile twice to make the navigation bar with dots appear.

## Outer Theme

It is possible to switch from a `miniframes` outer theme with navigation dots to a `split` outer theme with sections and subsections in the header. I suggest using the `miniframes` outer theme when subsections are not meaningful.

## License

All rights related to the logo are property of Karolinska Institutet. This template is under MIT license. See `LICENSE` file for more information.
