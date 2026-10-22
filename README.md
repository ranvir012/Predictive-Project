# Data

The project uses **city_day.csv** from the Kaggle dataset
[Air Quality Data in India](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india) (CPCB, 2015-2020).

It is **downloaded automatically** to `data/city_day.csv` the first time you run the script or notebook.
To do it manually: download the dataset from Kaggle, unzip, and copy `city_day.csv` into this folder.

Columns: `City, Date, PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene, AQI, AQI_Bucket`

Only for a quick test of the code, `../sample_data/sample_city_day_SYNTHETIC.csv` has the same columns but
**artificial** values. Never report results from it:
`AQI_DATA=sample_data/sample_city_day_SYNTHETIC.csv python src/aqi_kdd_pipeline.py`
