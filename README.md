# 🌾 KhetPrithvi
An India-first crop classification system using **IBM Foundation Models**  
(Prithvi-EO + Granite Time Series FM) fine-tuned on AgriFieldNet India.

## 🚀 Inspiration
Indian farms are small and fragmented. Global models fail here.  
We wanted to build an **India-first crop ID system** that works on small fields,  
uses SAR + optical fusion, and is explainable.

## ⚙️ Tech Stack
- Python, PyTorch, Hugging Face Transformers
- IBM Prithvi-EO Foundation Model
- IBM Granite Time Series Foundation Model (TinyTimeMixer)
- TorchGeo, Rasterio, Geopandas
- Streamlit (for demo)

## 📂 Repo Structure
- `train.py` → fine-tuning script
- `model.py` → backbone (Prithvi + TSFM)
- `app.py` → Streamlit demo dashboard
- `dataloader.py` → loads AgriFieldNet India polygons & features
- `demo/` → screenshots and charts

## 🔧 Installation
```bash
git clone https://github.com/Amandixit158/khetprithvi.git
cd khetprithvi
pip install -r requirements.txt
