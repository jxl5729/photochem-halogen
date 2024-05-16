int.rates.out.dat and outchem.dat are two of the main output files. I compress the two due to file
size restriction of 25 MB. When you unzip it, please put them back to the folder IO. 

atm_chem.out_expalined.pdf is a legacy explaination for the outcham.dat file. It can be useful.

atm_chem.f is the main code. Please ignore the chemical reaction comments as I do not keep track of
them for years. 

Critical chemical scheme can be found in folder CHEM and SETUP. 

Folder ATMCHEM.o are 'cache' like folder. You can understand it better in the makefile.

Folder INCLUDECHEM has all the common bloc. 

Folder DATA has all the photochemical data, including the chemical reaction involved. However the
kinetic data of non-photolysis reactions is called rates.f under folder SETUP. 

recommend running the code in a cluster. 
 
