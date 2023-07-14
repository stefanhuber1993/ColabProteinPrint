# ColabProteinPrint
Google Colab to convert an atomic model of a protein into a series of 3D printable stl files.

## Features
* PDB input file is split in backbone and amino acid parts
* Amino acids are oriented in a standardised way for 3D printing
* Residue number is printed on the C-alpha hydrogen atom
* Phi and psi angles are encoded directly into the printed model as little notches.
* Trans and cis peptide bonds included
* Parametric model with customizable bond thicknesses and tolerances

## Limitations
* Support for proline is implemented but yet ntested

## Example print

33 amino acid alpha helix, backbone in white, amino acids in orange
![IMG_20230714_140722-EDIT](https://github.com/stefanhuber1993/ColabProteinPrint/assets/16330304/8a745b9b-4086-485f-8b5e-9c05a8b3e5e4)
