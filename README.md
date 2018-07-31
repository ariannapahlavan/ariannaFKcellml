# ariannaFKcellml
Fenton Karma .cellml file for Chaste software
Dimensionless ODEs in Fenton-Karma model requires different translators.py file. Rename 'translatorpyforFK' as 'translators.py'
in chaste/python/pycml.
The cellml file is debugged and should successfully recompile to generate .hpp and .cpp.
Once .hpp and .cpp are generated, Cvode.hpp file has to be modified (See Fenton3Cvode.hpp).
After Cvode.hpp modifications, recompile and it should be ready for sending sims
