# DLL Workshop April 2019

This jupyter notebook has examples of a number of Pandas commands that I use often
to process/prepare the MITx datasets for further analysis.

For visualization, I use Plotly, and you'll see some basic examples of them here.

The de-identified sample data is in the dropbox folder, if you have access to it.

The pre_workshop_instructions.pdf has instructions on how to get data from Google
BigQuery, and setting up python environment in your computer, and links to other
related repos and resources.  

### Downloading data from BigQuery

1. You need a service account file (xxx.json) that you put in the same directory
as the get_bq_data.ipynb notebook.
2. Run the notebook. Adjust the directory parameters to tune where you want to
download stuff.
3. For large-scale downloading of files from GBQ to GCS, you may want to use the 
gsutil command-line feature (details inside the notebook).
