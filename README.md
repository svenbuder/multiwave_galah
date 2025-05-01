# GALAH meets X-Ray and Radio

A repository for the hands-on session *Optical stellar spectroscopic insights into multi-wavelength astronomy* of Day 1 (6 May 2025) of the [2025 Australia/eROSITA-DE multi-wavelength school](https://astronomyaustralia.org.au/event/2025-australia-erosita-de-multi-wavelength-school/).

You can find the slides in this repository [here](https://github.com/svenbuder/multiwave_galah/blob/main/multiwave_galah_slides.pdf).

## 0 Required python packages

- numpy
- matplotlib
- astropy
- healpy
- astroquery

## 1 The GALAH Survey

The **GAL**alactic **A**rchaeology with **H**ERMES (GALAH) Survey is a large high-resolution optical stellar spectroscopic survey.

| <!-- -->    | <!-- -->    |
|--|--|  
| Large | $N_\text{spectra} = 1\,085\,520$ |  
| High-Resolution | $R = 28\,000$|  
| Optical | $\lambda~/~\mathrm{nm} \in [471-490,565-587,648-674,759-789]$|  
| Stellar | $N_\star = 917\,588$ with apparent magnitudes $9 < V < 14\,\mathrm{mag}$ |
| Spectroscopic | Absorption lines of: Li, C, N, O, Na, Mg, Al, Si, K, Ca, Sc, Ti, V, Cr, Mn, Fe, Co, Ni, Cu, Zn, Rb, Sr, Y, Zr, Mo, Ru, Ba, La, Ce, Nd, Sm, and Eu|

<p align=center>
    <img src="https://github.com/svenbuder/galah_dr4_paper/blob/main/figures/galah_dr4_skymap_gaiadr3.png" alt="Skymap of GALAH DR4 with Gaia DR3 in the background (linked from the DR4 paper GitHub repository.)" width="75%"/>
</p>

### Access to GALAH catalogues

GALAH catalogues are provided as FITS files at https://cloud.datacentral.org.au/teamdata/GALAH/public/GALAH_DR4/catalogs/.

A more detailed description of how to download these catalogues can be found at https://www.galah-survey.org/dr4/overview/

## 2 GALAH x X-Ray

Go to notebook [multiwave_galah_xray_crossmatches.ipynb](https://github.com/svenbuder/multiwave_galah/blob/main/multiwave_galah_xray_crossmatches.ipynb)

<p align=center>
    <img src="https://github.com/svenbuder/multiwave_galah/blob/main/figures/47Tuc_stars_xray_or_galah.png" alt="Stars in 47Tuc with observations from eROSITA and GALAH DR4" width="50%"/>
</p>

## 3 GALAH x Radio Stars

Go to notebook [multiwave_galah_radio_stars.ipynb](https://github.com/svenbuder/multiwave_galah/blob/main/multiwave_galah_radio_stars.ipynb)

<p align=center>
    <img src="https://github.com/svenbuder/multiwave_galah/blob/main/figures/radio_ga_ga_hrd_kiel.png" alt="Radio Stars in GALAH DR4" width="50%"/>
</p>

<p align=center>
    <img src="https://github.com/svenbuder/multiwave_galah/blob/main/figures/spectral_zoom_170205003401240.png" alt="Example spectra of a Radio Star" width="50%"/>
</p>

## 4 GALAH x InterStellar Medium

Go to notebook [multiwave_galah_interstellar_medium.ipynb](https://github.com/svenbuder/multiwave_galah/blob/main/multiwave_galah_interstellar_medium.ipynb)

<p align=center>
    <img src="https://github.com/svenbuder/multiwave_galah/blob/main/figures/galah_dr4_ism_k_longitude_vs_vlsr_cut_50.png" alt="Interstellar K local-standard-of-rest velocity across Galactic Longitude" width="50%"/>
</p>