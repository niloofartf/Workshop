# Copy the 'packmol' executable file into this directory.
#
# To pack 1000 carbon dioxide molecules in a 38 Angstrom cubic box and generate
# PDB and PSF file. Copy and paste the following command in your terminal:


# This command packs 1000 CO2 molecules and saves it as "packed_CO2.pdb"
./packmol < pack_box_1.inp

# This command generates new pdb and psf files using the VMD program
vmd < build_psf_box_1.tcl
