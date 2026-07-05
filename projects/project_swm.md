---
layout: default
title: swm
---


# High-Resolution Tractography of Superficial White Matter Across the Lifespan

This project was part of my research internship at the Peter S. Allen MRI Research Centre (University of Alberta).  
I worked on high-resolution diffusion MRI to study how superficial white matter (SWM) matures and changes across the human lifespan (5–74 years, n=185).

---

## Overview
Superficial white matter is the last region of the brain to myelinate, making it highly plastic but also vulnerable.  
Using advanced diffusion MRI and tractography, we mapped SWM and compared its maturation patterns to deep white matter (DWM).

This study is the **first to analyze SWM across the full human lifespan** using high-resolution diffusion MRI.

---

## My Contributions
- Processed diffusion MRI data using NLSAM denoising and FSL eddy correction.  
- Generated tissue segmentations directly in diffusion space using SynthSeg.  
- Built SWM seeding masks by combining dilated white matter and cortical gray matter.  
- Applied multi-shell CSD tractography (MRtrix3) with ACT and GM–GM filtering.  
- Implemented DBSCAN streamline clustering to remove outliers.  
- Analyzed lifespan FA/MD curves for SWM and DWM.

---

## Key Findings
- SWM reaches peak FA **later** than DWM (32 vs. 25 years).  
- SWM reaches minimum MD **later** than DWM (42 vs. 30 years).  
- SWM shows delayed maturation and delayed onset of age-related decline.  
- High-resolution (1.5 mm iso) data improved SWM delineation compared to previous studies.

---

## Tools & Skills
**MRtrix3**, **DIPY**, **FSL**, **SynthSeg**, **Python**, **Diffusion MRI**, **CSD tractography**, **Neuroimaging pipelines**

---

## Impact
This project improves understanding of SWM development and aging, with implications for neurological disorders such as autism, dementia, epilepsy, and multiple sclerosis.

Presented at:
- **International Society of Tractography Conference (2025):** High-resolution tractography shows later maturation of superficial white matter across the lifespan  
- **ISMRM (2026):** High‐resolution diffusion tractography shows altered superficial white matter in multiple sclerosis across the lifespan

