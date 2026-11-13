# ¹⁴CO₂ Assimilation Assay Calculator

---

## Overview

A browser-based calculator supporting the design and analysis of ¹⁴CO₂ assimilation assays in environmental and cultured microbial communities. Developed as Supplementary File S1 for:

> Ray AE, Tribbia DZ, Bernaud N, Laird T, Ferrari BC. *An improved and expanded protocol for ¹⁴CO₂ assimilation assays in environmental and cultured microbial communities.* Applied and Environmental Microbiology (in preparation).

## Features

**Experiment Designer**
- Calculates gasification bag preparation parameters following the full physical chemistry derivation (vessel ppmv, vessel volume, evolved CO₂ volume, µmol required, stock volume to pipette, zero-air to add, HCl volume)
- Computes total radioactivity (MBq) and checks against your institutional activity limit
- Calculates µCi and theoretical DPM per sample vial
- Flags whether sufficient ¹⁴CO₂ is available for the planned number of vials
- Generates a plain-language protocol summary

**Results Calculator**
- Converts raw LSC DPM readings to CO₂ fixation rates (nmol CO₂ g⁻¹ day⁻¹ for soils; pmol CO₂ mL⁻¹ day⁻¹ for cultures)
- Blank correction, % recovery, and mean ± SD calculated automatically
- Results can be copied to clipboard for import into Excel or R

## Usage

The tool runs entirely in your browser — no installation, no internet connection required after the page loads, and no data is transmitted or stored.

Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).

## Radiation safety

This calculator was developed under approval from the UNSW Radiation Safety Committee. Users must confirm their own institutional activity limits and update the calculator accordingly before use. The default limit (8.8 MBq per experiment) reflects the UNSW approval and must not be assumed to apply elsewhere.

## Contact

Angelique Ray — angelique.e.ray@nasa.gov

---

*This README will be updated with the full citation, DOI, and usage documentation upon publication.*
