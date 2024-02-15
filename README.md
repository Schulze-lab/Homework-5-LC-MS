# Assignments Week 5
# Introduction
The goal of this assignment is to get familiar with the basics of mass spectrometric data analysis. As a start, you will calculate m/z values for theoretical peptides. Afterwards, you will match them to a measured spectrum. This assignment should help you to understand concepts of mass, m/z, mass accuracy, and mass spectrometry peaks (pairs of m/z and intensity)
# Input data
An .idx.gz file with mass spectrometric raw data (from dataset PXD006121) has been uploaded to MyCourses. In addition, you will need the reference proteome for Neisseria meningitidis, which you have used in the previous weeks.
# Tasks and output files
1)	Perform an in silico tryptic digest for the reference proteome of Neisseria meningitidis, and calculate the m/z for all resulting peptides with a peptide length of 5 – 40. Assume that peptide ions have a charge of 2.
2)	What is the percentage of overlapping m/z values if you are working with an accuracy of 500 ppm? What about 5 ppm?
3)	For the MS1 spectrum #5160, match all your peptide ions (calculated m/z for z=2) against all peaks in the spectrum. How many peptide ions are matching?
4)	Plot the spectrum and highlight at least one matched peak in the spectrum by including a peak for the theoretical m/z of the matched peptide ion.
5)	Make sure to comment your code, so that others can read and understand it easily. 
6)	Create a README file describing how to run your code. Include requirements (e.g. Python packages that need to be installed) in that description, or as a separate requirements.txt file.
7)	Commit all your input files, scripts, and result files to your GitHub Classroom repository.
# Additional MS student tasks (bonus credit for BS students)
8)	Use the retention times predicted by DeepLC (Nm_peptides_deeplc_predictions.csv), and calculate how many overlapping m/z values would occur at each second of the chromatography? Feel free to use lab3_results.py as a starting point, and generate a plot with the number of overlapping peaks over retention time.
# Submission
You must submit the assignment through GitHub Classroom (or MyCourses) by 8 am February 22 to get full credit. 



