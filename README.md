# qeTocif
A short script to transform Quantum Espresso output files to Mercury-readable cif files. Intended only for full-cell relaxation outputs ran without symmetry and with trigonal unitcells. Requires zsh (http://www.zsh.org/ for Linux install with sudo apt-get install zsh) and openbabel (http://openbabel.org/wiki/Main_Page). 


NOTE: Need to alter the line 22 in order for the script to work:

~/work/templates/mercury.cif   <-- Needs to correctly reflect the location of mercury.cif
