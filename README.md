# Peptoid
Molecular simulation of self-assembled sequence-defined singly and triply charged polypeptoid micelles

Example of creating the topology 
prepgen -i TCA.ac -o TCA.prepi -f prepi -m mainchain.tca

Build Copolymers
tleap -s -f build_chain_6_tleap.in > build_chain_6_tleap.out


Gromacs compatible topology were then generated through ACPYPE
acpype -p FFF_AC.prmtop -x FFF_AC.inpcrd
