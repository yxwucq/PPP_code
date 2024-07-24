# Analysis of "Neutrophil-derived OSM fuels JAK-STAT3 signaling in keratinocytes in palmoplantar pustulosis patients: From single-cell sequencing to targeted therapy"

## Code
Repository consists of two parts: `pipelines/` and `ploting/`:

- `pipelines/` : Notebooks for processing raw data
- `ploting/`  : Notebooks for plotting

## Data
- All raw data are available on the Sequence Read Archive (SRA) database (accession number: PRJCA027884).
- All prcessed matrix data can be downloaded from https://doi.org/10.6084/m9.figshare.26362462
- All charts data are available in supplementary tables from the article

## Requirements
### scanpy version
- scanpy used in `pipelines/` is from https://github.com/ggit12/scanpy. Please refer to this [issue](https://github.com/theislab/single-cell-tutorial/issues/35) for more information
- scanpy used in `ploting` is the standard pypi version v1.10.0

### Other essential requirements
- python packages
```
biopython == 1.83
cellphonedb == 5.0.0
cellrank == 2.0.3
gseapy == 1.1.1
harmonypy == 0.0.9
ktplotspy == 0.2.3
scFates == 1.0.6
scikit-learn == 1.11.3
scvi-tools == 1.1.2
```
- R packages
```
CellChat == 4.3.2
anndata == 4.3.2
tidyverse == 4.3.0
```