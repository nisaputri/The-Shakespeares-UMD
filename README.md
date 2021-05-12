<h1> Shakespeare's World: Data Prep and Processing</h1>

<h2>Team Lead: Nisa Putri

Team Members: Andrew Carroll, Jonathan Chen, Josh Hershberger, Momina Khan</h2>

<h2> File Structure: </h2>

<b>Combine Newseletter Datasets.Rmd</b> - R script to merge seperated zooniverse manuscripts.

<b>Processing Data.ipynb</b> - Python script that extracted transcriptions from the Newsletter folder. Additionally, this script uses regex to extract information such as the Filename, Hamnet URL, and Luna URL.

<b>Cleaning Data.Rmd</b> - R script that removed duplicate lines from transcriptions and create datasets that only include key information from previously processed datasets.

<b>Unprocessed Data</b> - Contains copys of all the datasets that we used prior to any manipulation or cleaning done.

<b>Processed Data</b> - Contains datasets that had some cleaning/manipulation done, but needed to be imported into R for the final cleaning steps.

<b>Final Datasets</b> - Contains copies of datasets in their final form. Each dataset is to be delivered to a client who needed different types of data for their purposes. 


<h2> Python Packages:</h2>

<b>Pandas</b> - Used for data manipulation and creating dataframes that are exported to .csv files.

<b>os/pathlib</b> - Used to work with Newsletter file directories and extract transcriptions from .txt files.


<h2>R Libraries</h2>

<b>tidyverse</b> - Used for transforming and final cleaning of processed datasets. 
