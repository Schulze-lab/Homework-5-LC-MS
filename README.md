# Assignments Week 5
# Introduction
The goal of this assignment is to navigate through the measurement file from an HPLC-MS/MS analysis. Working through the tasks, you will look at both the chromatography part, as well as some mass spectra, combining both levels of information.
# Input data
An .mzML file, the standard data format for HPLC-MS/MS runs, has been uploaded to myCourses. In addition, you can download the reference proteome for Haloferax volcanii, the model archaeon that has been analyzed in this HPLC-MS/MS run from UniProt.
# Tasks and output files
1)	Plot the total ion chromatogram (TIC), i.e. the intensity of all ions over time. You can use existing modules like pymzML.
2)	Plot an MS1 spectrum from the middle of the HPLC-MS/MS run (around 30 +/- 10 min). How many peaks are in that spectrum?
3)	The S-layer glycoprotein (CSG, UniProt ID P25062) is the sole component of the archaeal S-layer. A tryptic peptide from the CSG is VTAHILSVGR. Calculate the m/z for this peptide (using a charge of 2) – you can use existing modules like pyteomics, or create your own function for m/z calculation.
4)	Search for the VTAHILSVGR2+ ion in all MS1 spectra of the HPLC-MS/MS run. Extract the corresponding ion intensities and plot the chromatogram representing this peptide (ion intensities over time, also referred to as ion chromatogram).
5)	Make sure to comment your code, so that others can read and understand it easily. 
6)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
7)	Commit all your input files, scripts, and result files to your GitHub Classroom repository.
# Submission
You must submit the assignment through GitHub Classroom by 8 am Feb 23 to get full credit. 
# Bonus Credit
8)	From your previous assignments, use the functions to parse the Haloferax volcanii .fasta file, extract the protein sequence for CSG, and digest the whole protein into tryptic peptides. How many of those peptides can be found (on the MS1 level, assuming charges from 2 to 4) in the HPLC-mS/MS run? For each of those peptides, extract the ion chromatogram.


