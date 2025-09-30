# Shorea-robusta-forests-Study
## 📖 Overview
The study evaluates vegetation phenology of *Shorea robusta* forests in the Doon Valley (Western Himalayas) using MODIS and Sentinel-2 data (2017–2024).  
Environmental drivers such as elevation, land surface temperature (ΔLST), and precipitation (ΔPP) were integrated to model phenological dynamics.  

This repository provides **reproducible code** for:
- Extraction of MODIS NDVI and phenological metrics  
- MODIS LST seasonal composites and ΔLST / TNPI_LST computation  
- ERA5 precipitation composites and TNPI_PP computation  
- Sentinel-2 NDVI preprocessing, cloud masking, and TNPI calculation  

---

## 📂 Repository Contents
- `code/` – GEE JavaScript scripts  
  - `Code_S1_MODIS_LST.js` – MODIS LST, SOS/EOS, ΔLST, TNPI_LST  
  - `Code_S2_MODIS_NDVI.js` – MODIS NDVI time series and phenology metrics  
  - `Code_S3_ERA5_Precipitation.js` – ERA5 precipitation ΔPP and TNPI_PP  
  - `Code_S4_Sentinel2_TNPI.js` – Sentinel-2 NDVI processing and TNPI  

 

---

## ⚙️ Requirements
- [Google Earth Engine](https://earthengine.google.com/) account  
- GEE Code Editor (`https://code.earthengine.google.com/`)  

All scripts are written in **JavaScript for the GEE Code Editor**.  

---

## 🚀 Usage
1. Log in to [Google Earth Engine Code Editor](https://code.earthengine.google.com/).  
2. Copy-paste the scripts from the `code/` folder.  
3. Upload your ROI shapefile/GeoJSON into the GEE Assets or directly define it in the script.  
4. Run the scripts to generate NDVI, LST, precipitation composites, and TNPI layers.  
5. Export results as GeoTIFF/CSV to Google Drive.  

---

## 📄 License
This repository is licensed under the **MIT License** (feel free to modify based on your preference, e.g., CC-BY 4.0 for scientific use).  

---

## 🙏 Acknowledgements
- Space Applications Centre (SAC), ISRO  
- Geomatics Engineering Division, IIT Roorkee  
- Google Earth Engine for free satellite data access and processing
```

---

