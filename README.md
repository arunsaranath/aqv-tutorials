# 🌊 AQUAVERSE: Deep Learning for Water Quality
### Official Tutorial Series | Ocean Optics Conference 2026

<p align="center">
  <img src="https://img.shields.io/badge/Status-Under_Development-orange" alt="Status">
  <img src="https://img.shields.io/badge/Focus-MDN_&_Atmospheric_Correction-blue" alt="Focus">
  <a href="https://colab.research.google.com/">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</p>

This repository contains the comprehensive lesson plan and interactive tutorials for the **AQUAVERSE** framework. Designed for the Ocean Optics 2026 conference, these modules introduce users to Mixture Density Networks (MDNs) and their application in retrieving high-fidelity water quality metrics from satellite and spectral data.

---

## 📚 Lesson Plan

This tutorial is structured as an end-to-end pipeline, moving from theoretical foundations to real-world satellite applications.

### 1. Introduction to MDN & GLORIA Data
* **Goal:** Understand the spectral inputs and the architecture of Mixture Density Networks.
* **Highlights:** * Exploratory Data Analysis (EDA) of the **GLORIA** dataset.
  * Comparing classical Neural Networks vs. MDNs.
  * Interpreting model outputs and quantifying **uncertainty**.

### 2. MDN-AC: Atmospheric Correction
* **Goal:** Perform Atmospheric Correction (AC) on raw satellite imagery.
* **Highlights:** * Using APIs to fetch Top-of-Atmosphere (TOA) signals.
  * Converting TOA to Rayleigh-corrected reflectance ($\rho_{rc}$).
  * Executing the correction pipeline to derive Remote Sensing Reflectance ($R_{rs}$).

### 3. MDN-WQ: Water Quality Retrieval
* **Goal:** Extract biogeochemical products from corrected imagery.
* **Highlights:** * Applying MDN-WQ models to the output from Lesson 2.
  * Generating spatial maps for Chlorophyll-a and other water quality indicators.

---

## 🛠️ Exercises & Extensions

<details>
<summary><b>💪 Exercise 1: End-to-End Challenge (Click to Expand)</b></summary>
<br>
Test your knowledge by applying the full pipeline to a new, independent dataset. 
<ul>
  <li><b>Task:</b> Download, correct, and analyze a unique image.</li>
  <li><b>Resources:</b> We provide a "Starter" notebook with code gaps and a "Solution" notebook for post-session verification.</li>
</ul>
</details>

<details>
<summary><b>🧪 Optional: In-Situ Validation</b></summary>
<br>
Compare MDN-WQ performance against standard algorithms using your own 2D spectral measurements. 
<ul>
  <li>Validate model superiority with ground-truth data.</li>
  <li><i>Coming Soon:</i> Automated point-location extraction and correction (Projected: Late 2026).</li>
</ul>
</details>

---

## 🚀 Getting Started

1. **Clone the repo:**
   ```bash
   git clone [https://github.com/arunsaranath/aqv-tutorials.git](https://github.com/arunsaranath/aqv-tutorials.git)
