# Nyiragongo's Green Revolution: From Fiery Destruction to Lush Rebirth

## Introduction  
On 22nd May 2021, Mount Nyiragongo roared to life, painting the sky red and scarring the landscape. This project explores the **quantifiable environmental impact** of the eruption and the astonishing ecological recovery that followed.  
Using **Sentinel-2 satellite imagery**, we analyze vegetation change before and after the eruption to answer a key question:  
**How has vegetation changed since the Nyiragongo 2021 eruption?**

---

## Project Goals
- Assess the extent of the burnt areas caused by the eruption.
- Quantify long-term changes in vegetation health.
- Correlate post-eruption regrowth with volcanic ash mineral enrichment.

---

## Materials & Methods
- **Satellite Data:** Sentinel-2 SR (pre- and post-eruption 3-year composites)
- **Indices Used:**  
  - Normalized Burn Ratio (NBR) & Delta NBR for burnt area mapping  
  - Normalized Difference Vegetation Index (NDVI)  
  - Enhanced Vegetation Index (EVI)  
- **Tools:**  
  - Google Earth Engine (Python API)  
  - Geemap for visualization & exports  
  - Matplotlib & GeoPandas for local processing  

### Methodology Workflow
1. Create cloud-masked composites for 2019 (before) and 2022 (after).  
2. Compute NBR and NDVI indices before and after the eruption.  
3. Calculate Delta NBR to identify burnt areas.  
4. Analyze NDVI & EVI differences to assess vegetation recovery.  
5. Export resulting layers as GeoTIFFs for further analysis and map styling.

---

## Results
- **Burnt Areas:** Detected using Delta NBR (>0.3 threshold).  
- **Vegetation Recovery:** NDVI & EVI show a significant increase post-eruption.  
- Surprisingly, **areas initially scorched by lava** correspond to regions with **vigorous vegetation regrowth**.  
- **Reason:** Volcanic ash enriched the soil with minerals (phosphorus, potassium, calcium), acting as a natural fertilizer.

---

## Key Findings
> From ashes to emerald — Nyiragongo's eruption was not an ending but a dramatic new beginning.  
> The volcano’s fury led to lush greenery reclaiming the landscape.

---
