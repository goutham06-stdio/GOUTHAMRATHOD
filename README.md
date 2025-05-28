# Juruá AI Discovery: Mapping Hidden Sites with GPT and Remote Sensing

This project explores how AI and remote sensing can help uncover hidden archaeological sites in the Juruá River Basin of Brazil. By combining GPT-4.1, Sentinel-2 imagery, and NASA GEDI LIDAR data, it builds a framework to simulate vegetation anomaly detection and historical cross-referencing.

## 🌍 Project Objective

To create an AI-assisted pipeline that helps archaeologists locate potential ancient settlement sites in dense Amazonian jungle using:

- Multispectral satellite imagery (NDVI)
- LIDAR-based forest canopy analysis
- Historical and oral archives interpreted by GPT

## 📦 Dataset Sources

- **Sentinel-2 Satellite Imagery**: [USGS EarthExplorer](https://earthexplorer.usgs.gov/)
- **NASA GEDI LIDAR**: [Earthdata Search](https://search.earthdata.nasa.gov/search)
- **Textual Sources**:
  - Chronicles of the Amazon
  - Huni Kuin Oral Atlas

## 🛠️ Tools and Technologies

- **Python, Jupyter Notebook**
- **NumPy, Matplotlib, Rasterio**
- **scikit-learn, GeoPandas**
- **GPT-4.1 for text analysis**
- **Hugging Face Spaces** for demo interface

## 🚀 Demo

▶️ **Interactive NDVI Heatmap Interface**  
[Live Demo on Hugging Face](https://huggingface.co/spaces/aiarchaeo/jurua-ai-discovery)

## 📁 Project Files

- `jurua_ai_discovery.ipynb` — Jupyter Notebook with code and analysis

## 📌 Key Insights

- NDVI anomaly detection can highlight areas where vegetation has been disturbed
- LIDAR offers promise in revealing artificial mounds or clearings
- GPT-based cross-referencing of historical texts suggests site-prone regions

## 🔮 Future Work

- Integrate real-time NDVI from Copernicus API
- Add LIDAR elevation filtering
- Build an end-to-end anomaly detector model
- Collaborate with field archaeologists for validation

---

**Author:** Goutham Rathod  
🧠 Solo Submission to [OpenAI to Z Challenge on Kaggle](https://www.kaggle.com/competitions/openai-to-z-challenge)

