# WindFlow
Jupyter Notebooks and data used in Wind flow project - Blackford Hill (2025). Contains linear model (JH, WST, MS) and WindNinja output for Blackford Hill DTM, as well as raw measurement data collected on both days of measurements

- `Blackford_2M_DTM_PHASE5.tif` DTM - contains gridpoints and elevation
- `NBLidar4m....asc` - WindNinja flow files: wind velocity components
- `LinearWindModel.ipynb` contains derivation for linear model and a run over the DTM
- `BlackfordComparison.ipynb` runs windNinja output over DTM using `.asc` files
- `WindNinja_windward-leeward_comparison` plots correlation between WindNinja and windward/leeward/both measurements. adjust between `df[a_speed1]` and `df[a_speed2]` as necessry
- `KestrelCorrelation.ipynb` contains plot of correlation per averaging time for both kestrels on day 2. uses input `KestrelCorrelation.csv` containing `wind speed` and `time` columns
- `BlackfordWindDataFull(Day2).csv` include columns `TIME,JCMB WINDSPEED,JCMB WINDDIRECTION,KESTREL WINDSPEED,KESTREL WINDDIRECTION,ANEMOMETER 986 #TURNS,ANEMOMETER 986 LAT,ANEMOMETER 986 LON,ANEMOMETER 1280 #TURNS,ANEMOMETER 1280 LAT,ANEMOMETER 1280 LON` for day 1 and day 2 measurements
