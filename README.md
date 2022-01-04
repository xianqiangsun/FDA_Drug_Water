# FDA_Drug_Water
The water molecules are saved in the pdb files.\
In each PDB file, water molecules are deposited using the following format.

AtomType|ID|Atom|Name| ID|           X|     Y|      Z|Occupy|DeltaG|
HETATM    1 O    H2O     1      50.959  50.136  33.023 0.999  -5.9           O-1
HETATM    2 O    H2O     2      56.431  59.321  36.125 0.883  -1.4           O-1
HETATM    3 O    H2O     3      53.595  56.542  22.677 0.842  -4.3           O-1
HETATM    4 O    H2O     4      54.929  46.497  24.819 1.000  -3.8           O-1
HETATM    5 O    H2O     5      48.422  52.751  23.794 0.981  -3.5           O-1
HETATM    6 O    H2O     6      50.427  51.843  25.280 0.721  -3.3           O-1
  

The Unit for the "DeltaG column" is kJ/mol(Corresponding to the B-factor column in PDB file).\
The Occupy column shows the occupation rate of the hydration site by a watermolecule during the molecular dynamic simulations.

