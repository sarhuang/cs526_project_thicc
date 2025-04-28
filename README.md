# Tennessee's Hottest Industries by County Calculator (THICC)

**Assignment**: COSC 526 Final Project\
**Project Title**: Tennessee's Hottest Industries by County Calculator

**Project Description**: This notebook utilizes the Agency for Healthcare Research and Quality (AHRQ)'s Social Determinants of Health (SDOH) Database to train a Random Forest regression model to predict the best Tennessee counties for employment given a user's job industry, education level, and other socioeconomic variables. The user will see the top 5 best Tennessee counties/areas and the overall employment landscape in Tennessee for a given industry.

**Notebook Sections**:
- Data Preprocessing & Cleaning
    - Merging mutliple datasets into one
    - Handling empty values
    - Selecting features
- Creating Random Forest Model
- Implementation
    - Choropleth map creation
    - Interactive map using Plotly 

**Installation Instructions**: 
- Due to the large file size of the data, please find all the data in Harvard Dataverse (https://doi.org/10.7910/DVN/GIOAZY).
    - Make sure the **sdoh_2020_tract_1_0.xlsx** and **sdoh_2020_tract_1_0_data.csv** are in the data folder.
    - The shapefiles are already in the data folder.
- All code is in the "thicc.ipynb" Jupyter notebook.
- External libraries used:
    - geopandas - Pandas DataFrames with geometry support
    - scikit-learn - Machine learning library
    - ipywidgets - For interactive Jupyter dropdown widgets
    - plotly.express - Interactive visualization renderer 


**Use**:
The notebook offers interactive dropdowns that allow users to select an industry and education level and will automatically rerender the map. The availble visualizations are a static choropleth map and an interactive Plotly map for further investigation. 

**Contact Information**:
Email shuang24@vols.utk.edu for any questions.
