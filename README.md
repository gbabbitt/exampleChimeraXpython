This python script example script will externally control, open, and run ChimeraX.  The green fluorescent protein file will open and be colored by attribute of solvent exposure of each amino acid.  The python script uses the settings in the control file ChimeraXvis.ctl and looks for the PDB and attribute file in the folder with the same name.


TO RUN FROM TERMINAL/CMD PROMPT

/my/path/to/ucsf-chimerax/bin/ChimeraX color_by_attr_chimerax.py


might look something like this
$ /usr/lib/ucsf-chimerax/bin/ChimeraX color_by_attr_chimerax.py

NOTE: in Windows, place the contents of the repo in the bin folder for ChimeraX and open a cmd prompt and type
'ChimeraX color_by_attr_chimerax.py'

TO CHANGE FILES
open and rewrite ChimeraXvis.ctl 

NOTE: make sure 'attr' in .ctl file matches 'attribute' in .dat file
authors Rochester Inst Technol BIOL230 team under Dr. G.A. Babbitt (Harsh Srivastava, Breanna Callahan, Meghan Courtney, Cristina Guzman-Moumtzis, Cory Kornowicz)
