# Data Visualization of phreeqc
Jupyter notebooks to visualize the simulation results from phreeqc

## Data
There are 126 simulation outputs with the different parameters [job_summary.csv](data/job_summary.csv).  
job001_Beerling_original.out to job126_Beerling_original.out in [data](data).

## Single Job Visualization
The [instruction](documents/20231113_Library_of_possible_graphs.pdf) and the accompanying data is under [documents](documents).  

The "time" column in the output is in second, it needs to be converted to years or days.  

**note**: for the flood graph shown in the last page, one possible solution is that collecting the data (values) by depths and years as a matrix, then polting this matrix as an image.        

**Matplotlib Style**: [SciencePlots](https://github.com/garrettj403/SciencePlots) provides Matplotlib styles for scientific figures. It is useful to produce the publication-ready graphs. It may be used as an addon.   

