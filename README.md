# Virtual-screening-of-Non-Fullerene-Acceptor


## ***High-throughput screening for NFA molecules***
Supplementary information for *Computational identification of novel families of non-fullerene acceptors by modification of known compounds*, by Z-W Zhao, Ö H. O, D Padula, Y Geng and A Troisi.


## ***Geometries***
The optimized 27 geometries of the selected promising NFA candidates are gathered in the 27xyzfile.rar file.
They have been obtained via DFT/B35LYP/def2SVP optimization in Gaussian16. To split them, run
**obabel -ig09 *.log -oxyz -O opt_.xyz -m**
This will generate 27 .xyz file named opt_ID.xyz



## ***Structures***
To generate a 2-D representation of the 5159 geometries, use the smiles strings provided in the .csv file.



## ***Properties***
Computed properties are gathered in the .csv file provided. Each row contains one molecule. The columns contain the properties of 5159 molecules and also some properties for re-optimized 27 molecules. 



## ***Miscellanea***
•	ID: identifier of molecule
•	smiles: smiles string for the molecule



## ***Computed Properties***
•	HOMO: DFT/B3LYP/def2SVP HOMO energy for the molecule (eV)
•	LUMO: DFT/B3LYP/def2SVP LUMO energy for the molecule (eV)
•	LUMO+1: DFT/B3LYP/def2SVP LUMO+1 energy for the molecule (eV)
•	f(S1): TDDFT/M062X/def2-TZVP//B3LYP/def2SVP oscillator strength of the first singlet excited state
•	f(S2): TDDFT/M062X/def2-TZVP//B3LYP/def2SVP oscillator strength of the second singlet excited state
•	E(S1): TDDFT/M062X/def2-TZVP//B3LYP/def2SVP energy of the first singlet excited state (eV)
•	E(T1): TDDFT/M062X/def2-TZVP//B3LYP/def2SVP energy of the first triplet excited state (eV)
•	dS1T1: TDDFT/M062X/def2-TZVP//B3LYP/def2SVP energy difference of the first triplet and singlet excited state (eV)
•	ΔELL+1: DFT/B3LYP/def2SVP LUMO+1 energy difference of LUMO and LUMO+1 energy for the molecule (eV)
•	fmax: TDDFT/M062X/def2-TZVP//B3LYP/def2SVP oscillator strength of the excited state with strongest absorption of the three lowest states
•	consensus Log Po/w: lipophilicity of the molecule measured by the logarithm of octanol/water partition function 
