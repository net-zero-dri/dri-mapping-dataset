# The DRI Mapping Dataset

This dataset was generated as an output for the DRI Mapping exercise carried out during
the UKRI Net Zero Digital Research Infrastructure (DRI) Scoping Project undertaken from
2021-2023. The final report of this work is available from:

https://doi.org/10.5281/zenodo.*****************************

This dataset, and its accompanying code and metadata files are available from:

https://doi.org/10.5281/zenodo.7784877 

Or on GitHub at:

https://github.com/net-zero-dri/dri-mapping-dataset

## Contents

This repository contains the following files:

- `full_questionnaire.pdf` - a table of all questions that were asked in the questionnaire.




## Guidance on working with the DRI Mapping Dataset

The following information gives guidance on reading and working with the dataset.

## Dataset file and structure

The dataset file is contained within this repository:

```
dri_mapping_dataset.csv
```

It can be accessed directly from this public URL:

https://github.com/net-zero-dri/dri-mapping-dataset/blob/main/dri_mapping_dataset.csv

The dataset contains a simple table, as follows:

- The first row contains column headings:
  - The first column is the record number
  - Excluding the first cell (which is the record number), these map to questions asked in 
    DRI Mapping Survey
  - The headings use short codes
  - A CSV file is provided, `column_descriptions.csv`, containing the columns:
    - Column name
	- Descriptive name
	- Original survey question
	
- There are 44 records in total

## Working with the dataset

The dataset is written to a comma-separated-variables (CSV) file so it can be read by any
software designed for data analysis as well as standard desktop applications such as 
Excel and Notepad.

### Importing the dataset into Excel

You can open the CSV file directly into Microsoft Excel. There are many guides on how to do
this, such as:

https://support.microsoft.com/en-us/office/import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba


### Working with the dataset in a Jupyter Notebook

Jupyter Notebooks are powerful interactive tools that allow you to write, annotate and 
execute Python code within your web-browser. We have provided a Notebook with examples of 
how to work with the DRI Mapping dataset. See:

https://github.com/net-zero-dri/dri-mapping-dataset/blob/main/example-notebook.ipynb

You can execute the Notebook directly on the free Binder service, from here:



https://hub.gke2.mybinder.org/user/roocs-roocs-utils-inssttkb/lab/tree/notebooks/examples.ipynb


https://mybinder.org/v2/gh/roocs/roocs-utils/HEAD

https://mybinder.org


The Python software environment required to run the notebook is defined in the file:

```
environment.yml
```



