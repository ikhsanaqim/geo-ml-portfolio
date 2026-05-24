# 🌊 Geo-ML Portfolio — Ikhsan Mustaqim

**Weekly geospatial data science notebooks** | Marine · Environmental · Remote Sensing · AI/ML

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)](https://python.org)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ikhsanaqim-blue?logo=linkedin)](https://linkedin.com/in/ikhsanaqim)
[![GitHub](https://img.shields.io/badge/GitHub-ikhsanaqim-black?logo=github)](https://github.com/ikhsanaqim)

> *One notebook per week. Real data. Open source. Runnable in Google Colab.*

---

## 📂 Project Index

### 🌡️ Ocean & Climate

| # | Project | Topic | Tools | Colab |
|---|---|---|---|---|
| 01 | [SST Indonesia 2021–2025](./01_sst_indonesia/) | Sea Surface Temperature trend & anomaly | xarray · Cartopy · Plotly | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/01_sst_indonesia/sst_indonesia_visualization.ipynb) |
| 02 | [Pasang Surut BMKG](./02_tidal_bmkg/) | Download & visualisasi time-series pasang surut | Pandas · Matplotlib | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/02_tidal_bmkg/notebook.ipynb) |
| 03 | [Marine Heatwave Indonesia](./03_marine_heatwave/) | Deteksi anomali SST dengan Isolation Forest | Scikit-learn · Plotly | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/03_marine_heatwave/notebook.ipynb) |
| 04 | [ENSO vs SST Indonesia](./04_enso_sst/) | Korelasi ONI index vs SST 40 tahun | Xarray · Plotly | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/04_enso_sst/notebook.ipynb) |
| 05 | [Klorofil-a Laut Banda](./05_chlorophyll_banda/) | Monitoring klorofil-a bulanan dari MODIS | GEE · Folium | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/05_chlorophyll_banda/notebook.ipynb) |

### 🌿 Land & Forest

| # | Project | Topic | Tools | Colab |
|---|---|---|---|---|
| 06 | [NDVI Kalimantan](./06_ndvi_kalimantan/) | Pemetaan tutupan vegetasi dari Sentinel-2 | GEE · Python | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/06_ndvi_kalimantan/notebook.ipynb) |
| 07 | [Deforestasi Kalimantan](./07_deforestation/) | Animasi perubahan tutupan hutan 2000–2023 | GEE · Hansen GFC | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/07_deforestation/notebook.ipynb) |
| 08 | [Deforestasi Sumatera](./08_deforestation_sumatra/) | Time-series deforestasi 20 tahun | GEE · Plotly | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/08_deforestation_sumatra/notebook.ipynb) |
| 09 | [Mangrove Change Detection](./09_mangrove/) | Deteksi perubahan mangrove multi-temporal | GEE · Landsat | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/09_mangrove/notebook.ipynb) |

### 🚢 Maritime

| # | Project | Topic | Tools | Colab |
|---|---|---|---|---|
| 10 | [Fishing Effort Indonesia](./10_fishing_effort/) | Heatmap aktivitas kapal dari GFW API | GFW API · Folium | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/10_fishing_effort/notebook.ipynb) |

### 🏙️ Urban

| # | Project | Topic | Tools | Colab |
|---|---|---|---|---|
| 11 | [Urban Heat Island Bandung](./11_uhi_bandung/) | LST analysis + ML prediction | Landsat · Scikit-learn | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ikhsanaqim/geo-ml-portfolio/blob/main/11_uhi_bandung/notebook.ipynb) |

---

## 🗓️ Update Schedule

Satu notebook baru setiap minggu. Follow di [LinkedIn](https://linkedin.com/in/ikhsanaqim) untuk notifikasi.

---

## 🔧 How to Run

Setiap notebook dirancang untuk berjalan langsung di **Google Colab** tanpa setup lokal:

1. Klik badge **Open in Colab** pada project yang diinginkan
2. `Runtime` → `Run all`
3. Semua dependency di-install otomatis di cell pertama

Untuk menjalankan secara lokal:
```bash
git clone https://github.com/ikhsanaqim/geo-ml-portfolio.git
cd geo-ml-portfolio
pip install -r requirements.txt
jupyter notebook
```

---

## 📦 Common Dependencies

```
xarray>=2023.0
cartopy>=0.22
plotly>=5.18
pandas>=2.0
numpy>=1.24
requests>=2.31
matplotlib>=3.7
pillow>=10.0
earthengine-api>=0.1.370
geemap>=0.28
scikit-learn>=1.3
folium>=0.15
```

---

## 🔗 Related Repositories

| Repository | Description |
|---|---|
| [tidal-prediction-ml](https://github.com/ikhsanaqim/tidal-prediction-ml) | Deep learning GRU untuk prediksi anomali pasang surut (divalidasi BMKG) |
| FloodGuard *(coming soon)* | WebGIS prediksi risiko banjir rob Semarang berbasis GEE + ML |
| Carbon Stock Indonesia *(coming soon)* | Pemetaan stok karbon hutan & gambut Indonesia |
| Dark Vessel Detection *(coming soon)* | Deteksi kapal illegal dari SAR Sentinel-1 + AIS |

---

## 📚 Data Sources

| Dataset | Source | License |
|---|---|---|
| NOAA OISST v2.1 | NCEI / NOAA | Public Domain |
| Sentinel-1/2 SAR & Optical | ESA Copernicus | Free & Open |
| Landsat 8/9 | USGS | Public Domain |
| Hansen Global Forest Change | UMD / GEE | CC BY 4.0 |
| Global Fishing Watch AIS | GFW | CC BY-SA 4.0 |
| MODIS Ocean Color | NASA | Public Domain |

---

## 👤 About

**Ikhsan Mustaqim** — Geospatial Data Scientist | Marine & Environmental AI

Fresh graduate Oseanografi Universitas Diponegoro (IPK 3.79) dengan spesialisasi di GIS, remote sensing, dan machine learning untuk aplikasi kelautan dan lingkungan. Membangun 3 aplikasi WebGIS live, berkontribusi pada 6 publikasi ilmiah terindeks, dan memimpin proyek hibah pemerintah Rp 124 juta.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://linkedin.com/in/ikhsanaqim)
[![Email](https://img.shields.io/badge/Email-ikhsanaqim776%40gmail.com-red?logo=gmail)](mailto:ikhsanaqim776@gmail.com)

---

*If this repository is useful, consider giving it a ⭐*
