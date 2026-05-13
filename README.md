[![DOI](https://zenodo.org/badge/942143689.svg)](https://doi.org/10.5281/zenodo.20153518)


# urban-walkability-insights
Code for "Data-driven insights on urban walkability" paper


| File | Description |
|------|------------|
| `isochrone_extraction.ipynb` | Generating pedestrian isochrones for analysis. |
| `isochrone_urban_form_static.ipynb` | Extracting static urban features within 15/5-minute walk isochrones. |
| `isochrone_urban_form_multiyear.ipynb` | Extracting temporally variant urban features within 15/5-minute walk isochrones. |
| `ERA5_data_extraction.ipynb` | Processing ERA5 weather data for integration. |
| `data_processing.ipynb` | Processing urban form and pedestrian count data. |
| `model_selection.ipynb` | Comparing the performance of multiple models for predicting pedestrian counts. |
| `modeling.ipynb` | Modeling urban form features to analyze their relationship with pedestrian counts. |
| `partial_dependence_plots.ipynb` | Plotting partial dependence of urban features on pedestrian counts. |
| `residual_spatial_autocorrelation_check.ipynb` | Checking residual spatial autocorrelation. |

**Usage**

Run the Jupyter notebooks in the order listed above to reproduce the analysis.

**Data Sources**

Please refer to the [Data Sources](./DATA_SOURCES.md) document.
