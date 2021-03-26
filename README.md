# Polycrystalline graphene samples

Polycrystalline graphene samples generated for the paper "Efficient structural relaxation of polycrystalline graphene models", Federico D’Ambrosio, Joris Barkema and Gerard T. Barkema, to be published (2021).

- 3200 atoms at 625 eV
- 3200 atoms at 200 eV
- 10024 atoms at 696 eV
- 20000 atoms at 1488 eV 

The samples are available under [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/legalcode). If you're using them for your research, we would appreciate a citation. 

The samples are tab-separated files with the following format.

A prelude with:
```
Periodic boundaries size on the x-axis
Periodic boundaries size on the y-axis
Angle (ignored in single layer graphene)
Energy (for reference)
```
Followed by the location of all the atoms as:
```
AtomId Position (x)  Position (y)  Position (z) 
```
Finally, the bonds:
```
BondId Atom1 Atom2
```
