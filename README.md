# MeteoScape

This repository provides scripts to run MeteoScape on three tropical cyclone cases, each with its own folder:
- <a href="https://github.com/pascaloettli/MeteoScape/tree/main/Tropical%20Cyclone/2020-12.DOLPHIN">TC "Dolphin" (2020)</a>
- <a href="https://github.com/pascaloettli/MeteoScape/tree/main/Tropical%20Cyclone/2021-08.NEPARTAK">TC "Nepartak" (2021)</a>
- <a href="https://github.com/pascaloettli/MeteoScape/tree/main/Tropical%20Cyclone/2022-08.MEARI">TC "Meari" (2022)</a>

Each folders contains input data (anndata format) and scripts (R and Python) to 1) read the original NetCDF data (to be put in the <a href="https://github.com/pascaloettli/MeteoScape/tree/main/Tropical%20Cyclone/Data">Data</a> folder), 2) run MeteoScape.

- <code>adata.h5ad</code>: input data for MeteoScape
- <code>adata.Midpoints.KNN.HD.h5ad</code>: result of MeteoScape
- <code>Write_Anndata_For_MeteoScape.ipynb</code>: read NetCDF and write adata.h5ad
- <code>MeteoScape.ipynb</code>: read adata.h5ad and write adata.Midpoints.KNN.HD.h5ad
- <code>Figures_MeteoScape.ipynb</code>: different plots from MeteoScape (written in <code>figures</code> folder) 
  
MeteoScape is based on <a href="https://github.com/yusuke-imoto-lab/CellMap">CellMap</a>.

NetCDF data are available on Zenodo repository: <a href="https://doi.org/10.5281/zenodo.11064128"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.11064128.svg" alt="DOI"></a> and should be downloaded inside the <code>Data</code> folder.



