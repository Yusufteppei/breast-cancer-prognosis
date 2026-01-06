# breast-cancer-prognosis
An ongoing project predicting prognosis using transcriptomic and clinical data.

## DATA DOWNLOAD

ON LINUX:

`bash

git clone git@github.com:Yusufteppei/breast-cancer-prognosis.git
gdc-client __raw/gdc_manifest.2025-12-19.100010.txt
`

## COMBINE DATA FROM EACH 


Run the consolidate.ipynb notebook to generate the "__cleaned/tpm_unstranded.tsv" file

Finally, the `__cleaned/model.ipynb` has all its dependencies.
