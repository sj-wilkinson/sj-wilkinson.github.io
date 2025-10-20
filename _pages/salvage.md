---
permalink: /salvage/
title: "SALVAGE: The SDSS-ALMA Legacy Value Archival Gas Exploration"
author_profile: true

---

## What is SALVAGE?

The SDSS-ALMA Legacy Value Archival Gas Exploration (SALVAGE) dataset combines optical data products from the Sloan Digital Sky Survey (SDSS) and molecular gas measurements from the Atacama Large (sub-)Millimeter Array (ALMA) archive to produce a sample of 277 "semi-resolved" galaxies. 

<img src="/images/SALVAGE.jpeg">

------

## How to Use SALVAGE

The SALVAGE (SDSS-ALMA Legacy Value Archival Gas Exploration) dataset provides reduced ALMA CO(1-0) cubes and derived molecular gas measurements for SDSS galaxies. This section offers a brief guide on accessing and using these data.

### Accessing the Data

All SALVAGE data products are publicly available through CANFAR:

- **Data Release:** [SALVAGE Public Data Release](https://www.canfar.net/storage/vault/list/salvage/data_release_18-08-25)  
- **Contents:**
  - `/data/atlas/` – Quicklook images of optical fields, moment0 maps, spectra, and higher-order products (PNG).  
  - `/data/cubes/` – Reduced ALMA cubes in FITS format for individual galaxies.  
  - `/data/moments/` – Derived moment maps (moment0, moment1, moment2) in FITS format.  
  - `/data/qa_failed/` – Cubes and moment maps for galaxies that failed quality assurance.  
  - `salvage_pub.csv` – Catalog of semi-resolved molecular gas measurements with galaxy properties, CO luminosities, molecular gas masses, SFRs, and quality flags.

### Using the Data

- Each FITS cube in `/data/cubes/` corresponds to a single galaxy and can be analyzed directly or used to derive moment maps.  
- Derived moment maps in `/data/moments/` match the cube filenames and are ready for analysis.  
- The catalog (`salvage_pub.csv`) provides a convenient summary of molecular gas measurements and associated stellar properties.

### Reproducing or Extending the Analysis

- All calibration and reduction scripts used to produce SALVAGE are available on GitHub: [SALVAGE Repository](https://github.com/sj-wilkinson/SALVAGE/tree/main)  
- Researchers can adapt these scripts for their own analyses or to reproduce the published data products.

------

## Citation

If you use SALVAGE, please cite:

> Wilkinson et al. (2025), *SDSS-ALMA Legacy Value Archival Gas Exploration (SALVAGE) - I: global star formation is governed by central (not global) molecular gas*.

------

## Contact

If you have any questions or comments, feel free to reach out by [email](#mailto:swilkinson@uvic.ca).