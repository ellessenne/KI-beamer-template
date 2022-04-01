# KI Beamer Template

A beamer template inspired by Karolinska Institutet.
The template is consistent with the Karolinska Institutet graphic identity guidelines (more details [here](https://internwebben.ki.se/en/graphic-rules)).

> _Edit 2022-04-01_: While this was accurate back in 2016 when this template was first developed, it might not be the case anymore.

## Requirements

A _standard_ LaTeX installation should do!

Note that this template uses Source Sans Pro and Source Code Pro fonts, as provided by the [`sourcesanspro`](https://ctan.org/pkg/sourcesanspro) and [`sourcecodepro`](https://ctan.org/pkg/sourcecodepro?lang=en) packages (both available on CTAN).

## Usage

1. Clone the repository (or download the theme file `beamerthemeKI.sty` and the logo `ki-logo_vert_neg_1.pdf`, and place them in the same folder of your `.tex` file);
2. Add `\usetheme{KI}` in your preamble;
3. Compile twice to make the navigation bar appear.

See the [included template](https://github.com/ellessenne/KI-beamer-template/blob/master/ki-beamer-template.tex) for more details.

## Outer Theme

It is possible to switch from a `miniframes` outer theme with navigation dots to a `split` outer theme with sections and subsections in the header.
I suggest using the `miniframes` outer theme when subsections are not meaningful.

## Contributing

Please feel free to [file an issue](https://github.com/ellessenne/KI-beamer-template/issues) if you spot components that haven't been themed or [open a Pull Request](https://github.com/ellessenne/KI-beamer-template/pulls) if you want  to contribute improvements or patches.

## License

All rights related to the logo are property of Karolinska Institutet.
All rights related to the fonts used in this theme are property of the respective copyright holders.
Finally, this template is under MIT license, see the `LICENSE` file for more information.
