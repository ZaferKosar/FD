This library is intented to be used for LAMMPS Molecular Dynamics (MD) Simulations.

zkdatabuiler -> Creates a data file resembling E.coli model including cellular confinemment, cherry model of Transcription Factors (TF), circular DNA polymer with specific binding sites.

zkdumpreader -> Reads the resulting dump file of LAMMPS MD simulations (only applicable to simulations run with data files produced from zkdatabuilder) and reports (in a csv) number of bound TFs at each timestep.

zkcurvefit -> Reads the zkdumpreaders output csv fike and provides curvefit points for the given values.

For more information, please see the comments in the modules.
Packages can also be installed using pip command.
