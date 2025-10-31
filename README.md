# AROT and RET Prediction Code

The following files have been used for the paper *Predicting Arrival Runway Occupancy Time and Rapid Exit Taxiway Selection from OpenSky Data* presented at the **13th OpenSky Network Symposium** in Norrköping, Sweden, November 6–7, 2025.

## Files

- **Data_Collection.ipynb**  
  Downloads OpenSky Network (OSN) data, performs preprocessing, determines AROT and RET, creates ADS-B trajectory snippets, conducts feature engineering, and compiles the final dataset.

- **Data_Collection_2.ipynb**  
  Adds additional features to the existing dataset.

- **Combined_Prediction_Model.ipynb**  
  Trains and evaluates the RET prediction model and the AROT prediction model.

- **Final_Table.csv**  
  Dataset generated after running `Data_Collection.ipynb`.

- **Final_Table_V2.csv**  
  Extended dataset generated after running `Data_Collection_2.ipynb` (used for the prediction models).

## Further Files

- **missing_icao24_data.csv** – Supplementary dataset containing missing aircraft type mappings *(used in Data_Collection.ipynb)*.  
- **missing_malw.csv** – Supplementary dataset providing maximum allowable landing weights *(used in Data_Collection.ipynb)*.  
- **ogd-smn_klo_t_historical_2020-2029.csv** – Historical weather data from MeteoSwiss (Kloten station, covering the period 2020–2024) *(used in Data_Collection_2.ipynb)*.  
- **ogd-smn_klo_t_recent.csv** – Recent weather observations from MeteoSwiss (Kloten station, year 2025) *(used in Data_Collection_2.ipynb)*.  
- **ogd-smn_meta_parameters.csv** – Metadata file for the MeteoSwiss OGD datasets.  
- **Plots** – Folder containing figures used in the manuscript as well as additional figures not included in the paper.  
- **polygon_plot.ipynb** – Visualization of runway and taxiway polygons at Zurich Airport.  
- **stand_plot.ipynb** – Visualization of stand polygons at Zurich Airport.

