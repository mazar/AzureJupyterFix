# AzureJupyterFix
This is a fix for "cannot import name DataError" in Azure Spark Jupyter
All it contains is following command to downgrade pandas from 0.23.0 to 0.22.0:

/usr/bin/anaconda/bin/conda install pandas=0.22.0
