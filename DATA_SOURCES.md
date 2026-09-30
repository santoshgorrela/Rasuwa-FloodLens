# Rasuwa FloodLens — Data Sources

## 1. Primary Satellite Data

### Sentinel-1 SAR

Purpose:
- Flood detection
- Pre-flood and post-flood comparison
- Water expansion detection
- Flood extent mapping

Main platform:
Google Earth Engine

---

## 2. Optical Satellite Data

### Sentinel-2

Purpose:
- Visual validation of flood extent
- Before/after comparison
- Surface and land-cover observation
- Supporting flood and damage assessment

---

## 3. Additional Satellite Data

### Landsat

Purpose:
- Supporting event imagery
- Visual comparison
- Additional change assessment where useful

### EOS-04 SAR

Purpose:
- Supporting SAR reference imagery
- Independent comparison with Sentinel-1

### ALOS-2

Purpose:
- Additional SAR reference
- Supporting disaster assessment

---

## 4. Infrastructure Data

### OpenStreetMap

Purpose:
Infrastructure impact analysis.

Layers:
- Roads
- Buildings
- Bridges
- Settlements
- Other available infrastructure

---

## 5. Water Data

### JRC Global Surface Water

Purpose:
- Identify permanent water bodies
- Remove permanent water from flood detection
- Improve flood extent estimation

---

## 6. Disaster / Validation Data

### Sentinel Asia

Purpose:
- Reference satellite products
- Event information
- Flood and damage assessment reference

### UNOSAT

Purpose:
- Flood/mudflow/rockflow reference
- Validation of our satellite-derived results

### Copernicus Emergency Management Service

Purpose:
- Reference damage information
- High-resolution disaster mapping
- Validation and visual comparison

---

## 7. Study Event

Event:
August 2026 Rasuwa Flood, Nepal

Study Area:
Rasuwa District and the affected river corridor.

Main Analysis:
Rapid Flood Mapping Using Sentinel-1 SAR.

---

## 8. Data Processing Platform

Google Earth Engine will be used for:

- Satellite image filtering
- Image preprocessing
- SAR analysis
- Flood detection
- Area calculation
- Geospatial analysis
- Map visualization

---

## 9. Final Data Flow

Satellite Data
→ Image Processing
→ Flood Detection
→ Flood Extent
→ Infrastructure Overlay
→ Impact Analysis
→ Interactive Dashboard
→ Decision Support
