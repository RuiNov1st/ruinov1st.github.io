---
title: "Photometric redshift estimation for emission line galaxies of DESI Legacy Imaging Surveys by CNN-MLP"
collection: research
permalink: /research/elg_zphot
date: 2025-05-29
venue: "Publications of the Astronomical Society of Australia (PASA)"
paperurl: "https://doi.org/10.1017/pasa.2025.10056"
doi: "10.1017/pasa.2025.10056"
authors: "Shirui Wei et al."
highlight: "Combines DESI Legacy Imaging Surveys images and photometric catalogs with a CNN-MLP model to improve photometric redshift estimation for emission-line galaxies."
journal_url: "https://doi.org/10.1017/pasa.2025.10056"
representative_image: "elg_zphot/model.png"
figure_caption: "CNN-MLP architecture combining DESI Legacy Imaging Surveys image cutouts and photometric catalog measurements for ELG photometric redshift estimation."
keywords:
  - Photometric redshift
  - Emission-line galaxies
  - DESI Legacy Imaging Surveys
  - Multimodal deep learning
citation: 'Shirui Wei et al. (2025). "Photometric redshift estimation for emission-line galaxies..." <i>PASA</i>. 42, e092.'
excerpt: >
  Emission line galaxies (ELGs) are one of the main targets for the DESI survey. 
  We developed a multimodal deep learning model to integrate photometric images and catalogs, achieving significant improvements in redshift estimation.
  <br/><br/>
  <img src='/images/elg_zphot/model.png' style='width: 100%; max-width: 600px; display: block; margin: 0 auto;'>
---

Emission line galaxies (ELGs) are one of the main targets for the DESI survey, serving as direct tracers of the star-forming period of the Universe. Target selection for ELGs relies heavily on photometric redshift. **An accurate** photometric redshift estimation is crucial to decrease the selection failure rate and improve completeness.

In this work, we developed a multimodal deep learning model to integrate **two types of data**: photometric images and catalogs, aiming to improve current redshift estimation precision.

### Key Findings

**1. Performance Improvement**

Results show that our multimodal model achieves a **significant improvement** compared to using only images or photometric catalogs.

<figure style="text-align: center; margin: 20px 0;">
  <img src='/images/elg_zphot/tab1.png' style="max-width: 100%; border: 1px solid #ddd; padding: 5px; border-radius: 4px;">
  <figcaption style="color: #666; font-size: 0.9em; margin-top: 5px;"><i>Table 1: Performance comparison across different methods.</i></figcaption>
</figure>

**2. Redshift and Luminosity Dependence**

The model performs better for low-redshift and bright sources compared to faint and high-redshift sources. Our analysis shows the model is robust across different ELG types.

<figure style="text-align: center; margin: 20px 0;">
  <img src='/images/elg_zphot/z_mag.png' style="max-width: 80%;">
  <figcaption style="color: #666; font-size: 0.9em; margin-top: 5px;"><i>Figure 2: Redshift and magnitude distribution analysis.</i></figcaption>
</figure>

**3. Outlier Analysis**

Outliers are mainly located in the low-redshift and faint region. Our investigation suggests that the **lack of training samples** in this specific domain is the primary contributor to these prediction errors.
