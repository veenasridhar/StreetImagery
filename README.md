# CityGML Parsing & Mapillary Integration
A comprehensive Python project for parsing CityGML files, extracting building footprints and attributes, and integrating street-level imagery from Mapillary.

## Project Overview
This project processes CityGML 1.0 files (Level of Detail 2) to extract building information and visualize it alongside street-level imagery. The implementation includes:

-Building footprint extraction and visualization
-Building attribute parsing and CSV export
-Mapillary street-view image integration

##Installation & Setup
1. Download & unzip the files
2. Create virtual environment
   ```bash
   python -m venv citygml_env
   citygml_env\Scripts\activate   # On Windows
3. Install Dependencies
    ``` bash
    pip install -r requirements.txt
4. Run the Noteboook
    Make sure the file 690_5334.gml is in the same directory as the notebook file.
5. Expected Outputs
    Visulaisations are stored as map.html and static_plot.png

