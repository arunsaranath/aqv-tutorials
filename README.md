# 🌊 AQUAVERSE: Deep Learning for Water Quality
### Official Tutorial Series | Ocean Optics Conference 2026

<p align="center">
  <img src="https://img.shields.io/badge/Status-Under_Development-orange" alt="Status">
  <img src="https://img.shields.io/badge/Focus-MDN_&_Atmospheric_Correction-blue" alt="Focus">
  <a href="https://colab.research.google.com/">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</p>

---

## 📖 Overview
This repository contains the full lesson plan and interactive tutorials for the **AQUAVERSE** framework. It is designed for presentation at the **Ocean Optics Conference (August 2026)** and serves as a permanent introduction for new users to MDN (Mixture Density Network) packages and their application to geophysical datasets. Selected WQ products generated using our MDN pipelines are available for visualization and download via NASA's **<a href="https://ladsweb.modaps.eosdis.nasa.gov/stream/" target="_blank" style="color:#0056b3;text-decoration:underline;font-weight:bold;"> Satellite-based Tool for Rapid Evaluation of Aquatic environMents (STREAM)</a>** website.

## 📚 Lesson Plan
Each lesson is designed as a standalone Jupyter Notebook, moving from spectral foundations to end-to-end satellite workflows.

### 1. Introduction to MDN & GLORIA Data
* **Content:** Introduction to spectral data using the **GLORIA** dataset.
* **Key Topics:** Spectral visualization, MDN vs. Classical Neural Networks, output formats, and quantifying **uncertainty**.

### 2. MDN-AC: Application to Satellite Imagery
* **Content:** Walking through the Atmospheric Correction (AC) pipeline.
* **Key Topics:** API-based TOA signal retrieval, conversion to Rayleigh-corrected reflectance ($\rho_{rc}$), and performing the correction to $R_{rs}$.

### 3. MDN-WQ: Product Generation
* **Content:** Applying MDN-WQ to the corrected imagery from Lesson 2.
* **Key Topics:** Generating biogeochemical products and final spatial mapping.

### 4. Exercise 1: End-to-End Application
* **Content:** A hands-on challenge for participants to apply the pipeline to a different image.
* **Note:** Includes a "Starter" notebook with code blocks missing and a "Solution" notebook for post-session review.

---

## 🛠️ Extensions & Advanced Use
<details>
<summary><b>🧪 Optional: Application to 2D Spectral Data (Click to Expand)</b></summary>
<br>
Originally conceived to allow users to apply MDN-WQ to their own <i>in situ</i> measurements. This section provides a framework for algorithm validation and comparison against standard models.
</details>

---

## 🏛️ Team & Maintenance
These tutorials are created and maintained by the **Freshwater Sensing Group**, affiliated with **SSAI** and **NASA GSFC-619.0**.

<h4>Technical Contacts</h4>
<table style="width: 100%; border-collapse: collapse;">
    <thead>
        <tr style="border-bottom: 2px solid #ddd;">
            <th style="text-align: left; padding: 12px;">Domain</th>
            <th style="text-align: left; padding: 12px;">Section Lead</th>
            <th style="text-align: left; padding: 12px;">Email</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="padding: 10px; border-bottom: 1px solid #eee; font-weight: 500;">BPs & IOP Products</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;">Ryan E. O'Shea</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;"><a href="mailto:ryan.oshea@ssaihq.com">ryan.oshea@ssaihq.com</a></td>
        </tr>
        <tr>
            <td style="padding: 10px; border-bottom: 1px solid #eee; font-weight: 500;">Uncertainties</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;">Arun Saranathan</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;"><a href="mailto:arun.saranathan@ssaihq.com">arun.saranathan@ssaihq.com</a></td>
        </tr>
        <tr>
            <td style="padding: 10px; border-bottom: 1px solid #eee; font-weight: 500;">Atmospheric Correction</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;">Akash Ashapure</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;"><a href="mailto:akash.ashapure@ssaihq.com">akash.ashapure@ssaihq.com</a></td>
        </tr>
        <tr>
            <td style="padding: 10px; border-bottom: 1px solid #eee; font-weight: 500;">Stream Website</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;">William Wainwright</td>
            <td style="padding: 10px; border-bottom: 1px solid #eee;"><a href="mailto:william.wainwright@ssaihq.com">william.wainwright@ssaihq.com</a></td>
        </tr>
    </tbody>
</table>

---
<p align="center">
  <i>Part of the NASA GSFC-619.0 Freshwater Sensing Initiative.</i>
</p>
