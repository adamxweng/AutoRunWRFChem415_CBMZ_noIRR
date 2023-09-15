# AutoRunWRFChem CBMZ with nudging for 4.1.5 (no IRR support yet)
CBMZ: chem_opt = 9
# how to run:
source 01_envVar_set.sh
source ~/.bash_profile
bash 02_realnoChem.sh && bash 03_megan.sh && bash 04_realChem.sh && bash 05_mozbc.sh
