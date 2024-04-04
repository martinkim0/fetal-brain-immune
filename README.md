# Analysis for "Maternal Immune Activation Disrupts Proteostasis in the Fetal Brain"

## Raw data

Downloaded from: https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE148237

After downloading and unzipping the files, please place them in the `data/raw` directory.

## Convert TSVs to H5AD

To convert the TSV files to H5AD, run `notebooks/01_convert_anndata.ipynb`. The resulting H5AD
files will be saved to `data/h5ad`. 
