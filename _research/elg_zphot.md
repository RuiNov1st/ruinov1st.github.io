---
title: "Photometric redshift estimation for emission line galaxies of DESI Legacy Imaging Surveys by CNN-MLP"
collection: research
permalink: /research/elg_zphot
date: 2025-05-29
excerpt: >
  Emission line galaxies (ELGs) are one of the main targets for the DESI survey, serving as direct tracers of the star-forming period of the Universe. 
  An accurate photometric redshift estimation helps decrease the selection failure rate and improve completeness. 
  In Wei et al. 2025 <a href='https://doi.org/10.1017/pasa.2025.10056'>[Paper Link]</a>, we developed a multimodal deep learning model to integrate photometric images and catalogs, improving photometric redshift estimation for DESI ELGs.
  <br/><br/>
  <img src='/images/elg_zphot/model.png' style='width: 100%; max-width: 600px;'>
---

Emission line galaxies (ELGs) are one of the main targets for the DESI survey, providing direct tracers of the star-forming period of the Universe. ELG target selection is mainly based on photometric redshift. **An accurate** photometric redshift estimation would help to decrease the failure rate of selection and improve the completeness of selection.

In **Wei et al. 2025** <a href='https://doi.org/10.1017/pasa.2025.10056'>[PASA, 2025]</a>, we developed a multimodal deep learning model to integrate **two types of multimodal data**: photometric images and catalogs, to improve current redshift estimation precision.

### Key Findings:
* **Performance:** Results show that our multimodal model achieves a **significant improvement** compared to using only images or photometric catalogs.
<img src='/images/elg_zphot/tab1.png'>
* **Redshift and Luminosity Dependences:** The model performs better for low-redshift and bright sources compared to faint and high-redshift sources.
<img src='/images/elg_zphot/z_mag.png'>
* **Robustness:** The model is robust across different ELG types; differences basically stem from redshift, luminosity, and **sample** number distributions.

* **Outlier Analysis:** Outliers are mainly located in the low-redshift and faint region, where the **lack of samples** contributes to these prediction errors.

The improvement of using multimodal data for ELG photometric redshift will help improve ELG selection strategies.
