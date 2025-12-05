# 🌍 EO-bite
### Satellite processing engine for SENSORBITE

**EO-bite** is an open-source processing toolkit built for scalable Earth Observation (EO) analytics.  
At this stage, the project focuses primarily on **Sentinel Hub/CDSE integration** - covering data retrieval, spectral processing, SAR analysis, time-series generation and GIS-ready export.  
Support for STAC / OpenEO / CREODIAS Ecosystem will be expanded incrementally.

Designed as a core EO component within the **SENSORBITE ecosystem**, the repository enables fast prototyping of analytical workflows for agriculture, soil monitoring, water quality, contamination detection, crisis intelligence and environmental change assessment.

---

## 🚀 Current Focus

| Component | Status |
|---|---|
| **Sentinel Hub Process API/CDSE** | 🔥 main backend — primary data source |
| STAC / OpenEO | planned rollout — next milestone |
| CREODIAS | in roadmap |
| Local raster ingestion (COG/GeoTIFF) | modular integration phase |

➡️ **Right now we are driving development mainly through Sentinel Hub pipelines.**  
This allows fast iteration, multi-temporal requests, cloud masking and spectral processing directly on-demand.

---

## Key Features

| Category | Capabilities |
|---|---|
| **Acquisition** | Sentinel Hub API requests (S2 VSI, S1 GRD) |
| **Preprocessing** | Atmospheric mask, reprojection, clipping, COG |
| **Spectral Indices** | NDVI • EVI • NDMI • Chlorophyll • TSM/Sediments |
| **SAR Mapping** | Flood detection • Backscatter • Change metrics |
| **Time-Series** | Multi-date trend stacks • seasonal anomalies |
| **ML/Clustering** | KMeans pixel grouping • segmentation |
| **Export** | GeoTIFF/COG • GeoPackage • PostGIS output |

---

## Repository Structure

