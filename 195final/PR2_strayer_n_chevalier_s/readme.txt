Data Folder - This directory contains all of the raw CSV and happiness data which
was used to generate plots. As raw data was called, a function called geolocations
was used to lookup all lat/long data for each file. As the coordinates were called,
they were all cashed to a differenct CSV file. In this way, the slow geolocations
function was not called more than needed. All of this lat/long csv data is saved
in the data folder.

ideas.txt - This file contains all (or most) of the sources which were pulled from
as we found new data sets. All of the working code ended being merged together, 
so it is not included.

report_strayer_n_chevalier_s.ipynb - This is the final report. Because there were
two authors, there are two authors in title.

slides_strayer_n_chevalier_s.ipynb - This is the final presentation. It is an ipynb
full of plots from our report.