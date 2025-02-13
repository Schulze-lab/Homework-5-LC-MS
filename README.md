# Assignments Week 5
# Introduction
The goal of this assignment is to get comfortable with the basics of visualizing and interpreting mass spectra. As a start, you will calculate m/z values for theoretical peptides. Afterwards, you will match them to a measured spectrum. This assignment should help you to understand concepts of mass, m/z, mass accuracy, and mass spectrometry peaks (pairs of m/z and intensity)
# Input data
An .mzML file with mass spectrometric raw data (from dataset PXD019825) has been uploaded to MyCourses. In addition, you will need the reference proteome for Streptococcus mutans, which you have used in the previous weeks.
# Tasks and output files
1)	Perform an in silico tryptic digest for the reference proteome of Streptococcus mutans, and calculate the m/z for all resulting peptides with a peptide length of 5 – 40. Assume that peptide ions have a charge of 2.
2)	What is the percentage of overlapping m/z values if you are working with an accuracy of 500 ppm? What about 5 ppm?
3)	For an MS1 spectrum from the middle of the run, match all your peptide ions (calculated m/z for z=2) against all peaks in the spectrum. How many peptide ions are matching?
4)	Plot the spectrum and highlight at least one matched peak in the spectrum by including a peak for the theoretical m/z of the matched peptide ion.
5)	Make sure to comment your code, so that others can read and understand it easily. 
6)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
7)	Commit all your scripts and result files to your GitHub Classroom repository.
# Additional MS student tasks (bonus credit for BS students)
8)	Choose a single protein from the S. mutans proteome and calculate the m/z values (for charges 2-4) for all peptides from this protein. Search for these peptide ions across all MS1 spectra, and extract the intensities for all matching peaks (for each peptide separately). Plot those intensities as an extracted ion chromatogram against the retention time of the corresponding spectra (each peptide should be a separate trace in the graph, or separate graph).
# Submission
You must submit the assignment through GitHub Classroom (or MyCourses) by 8 am ET on February 20 to get full credit. 




