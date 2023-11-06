# November 6th, 2023
# Topology and parameter files developed by the group of Ville Kaila
#          Kailalab - https://villekaila.com/
# from 2010 (CCO-cytochrome c oxidase, cytochrome-b) 
#            - Heme-a,
#	     - Heme-a3,
#	     - Heme-b
#            - Cu-A 
#            - Cu-B
#      2014 Iron-sulfur clusters
#           - (4Fe4S)-4cys,                          
#	    - (4Fe4S)-3cys1His                       
#      2017 Quinone: ubiquinone(*), menaquinone and plastoquinone(*)
#      2019-2023 Ni-Fe Hydrogenase
#           - Ni-Fe in different catalytic states (*)    
#	    - 3Fe4S-3cys (*)                             
#      2021 Fe-Fe Hydrogenase
#           - Fe-Fe and (4Fe4S)-4cys   (*)               
#      2020-2023 Supercomplex CIII,CIV
#           - Heme-c
#           - Rieske center
#	    - Cu-3His-Hydroxyl 
#	    - Ac-PIM2, Ac2-PIM2 (*)
#
# (*)upload pending
#
# Main contributors:
# Ville Kaila
# Ana P. Gamiz-Hernandez
# Alexander Jussupow
# Daniel Riepl
# Mikael P. Johansson
#
# Files require previous charmm36 parameters and cgenff parameters - 
# 
# ref Cco - Charge parameterization of the metal centers in cytochrome c oxidase
#           M. P. Johansson, V. R. I. Kaila and L. Laakkonen
#           J. Comput. Chem. 2008 Vol. 29 Issue 5 Pages 753-767
#           DOI: 10.1002/jcc.20835
# ref:  Terminal Electron-Proton Transfer Dynamics in the Quinone
#       Reduction of Respiratory Complex I
#       A.P. Gamiz-Hernandez*, A. Jussupow, M.P. Johansson, and Ville R.I. Kaila*
#       J. Am. Chem. Soc. 2017, 139, 45, 16282-16288
#       [https://doi.org/10.1021/jacs.7b08486]
# ref:  Long-Range Proton-Coupled Electron Transfer Dynamics in the Obligate
#       Mycobacterial Supercomplex III2IV2
#       D. Riepl , A. P. Gamiz-Hernandez, et al and Ville R.I. Kaila*
#       (to be published)
#       [https://xxx]
#
# In order to facilitate their usage, toppar files are shared in sepparated 
# files and we included charmm-scripts examples of how to use them.
#       - charmm_examples
#
# Files included in this version

|--- README.txt
|-- cu.prm
|-- cu.rtf
|-- menaquinone.prm
|-- menaquinone.rtf
|-- README.usage.txt
|-- rieske.prm
|-- rieske.rtf
--- cgenff_files
|   --- menaquinol_from_cgenff.tail.str
|   --- mequinone_from_cgenff.tail.str
|-- charmm_examples
|   --- cytochrome_b.tgz
|   --- cytochrome_cc.tgz
|   --- cytochrome_c_oxidase.tgz
|   --- rieske_protein.tgz
|   --- superoxide_dismutase.tgz
|-- toppar36

