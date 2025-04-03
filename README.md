# TMDCs for CO<sub>2</sub> to methanol

This is a repository of all density functional theory (DFT) calculated data, related to the manuscript, "Ab-initio investigation of transition metal dichalcogenides for the hydrogenation of carbon dioxide to methanol" authored by Avaneesh Balasubramanian, Pawan Kumar Jha, Kaustubh Kaluskar, Sharan Shetty and Gopalakrishnan Sai Gautam. The manuscript is currently under review, but a pre-print is available at [arXiv](http://arxiv.org/abs/2504.01568). 

The goal of the project is to perform ab-initio computational calculations to compare the performance of transition metal dichalcogenides (TMDCs), MoSe<sub>2</sub>, WS<sub>2</sub> and WSe<sub>2</sub> nanosheets and nanoribbons with MoS<sub>2</sub>, as catalysts for the hydrogenation of carbondioxide (CO<sub>2</sub> gas) to methanol (MeOH). 

Each directory is labelled by the TMDC (or the gaseous species) considered in the calculation. Within each TMDC directory, there are subdirectories that contain files of its nanosheet and nanoribbon forms. _Sv_, _Dv_, _Tv_ denote single, double and triple vacancies of the chalcogenide atom in the nanoribbons or nanosheets. Within the directory for each vacant site; _CO2_, _MeOH_ and _DOS_ are folders containing files of the vacant structure adsorbing CO<sub>2</sub>, MeOH and the electronic density of states (DOS) of the vacant structure, respectively.

The _CONTCAR_, _POSCAR_ and _OUTCAR_ files are included for the structure relaxation calculations, and _vasprun_ files are included for the DOS calculations.

In case you use any of the data included here, we will appreciate a citation to our work at [arXiv](http://arxiv.org/abs/2504.01568).
