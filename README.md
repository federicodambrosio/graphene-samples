# Graphene samples

Polycristalline graphene samples generated according to the D’Ambrosio, Barkema and Barkema paper. 

The samples are tab-separated files with the following format.

- A prelude with:
```
Number of atoms
Periodic boundaries size on the x-axis
Periodic boundaries size on the y-axis
Angle (ignored for single layer graphene, will be discarded)
Energy (for reference, will be discarded)
```
Followed by the location of all the atoms as:
```
AtomId Position (x)  Position (y)  Position (z) 
```
Finally, the bonds:
```
BondId Atom1 Atom2
```
