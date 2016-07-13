# dia-fsa-sheet

A *very simple* sheet extension for finite state machines in Dia.
This can be useful if you want to further manipulate the machine
programmatically later.  Dia files are saved as XML and can be exported
as PNG, PDF, EPS, SVG, and a variety of other useful file formats.

An example FSA diagram that describes a machine that only accepts
`a*b*` is shown below.

![A's before B's](https://raw.githubusercontent.com/wiki/markroyer/dia-fsa-sheet/as_before_bs.svg
 "a*b*")

## Setup

First make sure that you have Dia installed.  On Debian you just need
to install the `dia` package.  Sourceforge also hosts
[Dia Document Editor](http://sourceforge.net/projects/dia-installer/files/)
for download.

Copy the files in the `sheets` and `shapes` directories to your local
user Dia directories.  On most Linux distributions, these files are in
the `~/.dia/sheets` and `~/.dia/shapes` locations.

Once the files are successfully copied, the new **FSA** sheet will
appear in the list of available sheets.

## Usage

The sheet contains the following two new shapes to help create FSA diagrams.

1. FSA - State
2. FSA - State Accepting

The initial state can be indicated by turning a State green (#00FF00).

The UML transition arrows can be used for state transitions.

## License

The project is licensed under the terms of the
[GPL3](https://www.gnu.org/licenses/gpl-3.0.en.html) license.

<!--  LocalWords:  dia fsa Sourceforge
 -->
