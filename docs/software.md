---
title: Software
layout: page
permalink: /software/
---
<style>
.item1 { grid-column-start: 1; grid-column-end: 3; grid-row-start: 1; grid-row-end: 1; font-size: 30px;}
.item2 { grid-column-start: 1; grid-column-end: 2; grid-row-start: 2; grid-row-end: 4;}
.item3 { grid-column-start: 2; grid-column-end: 3; grid-row-start: 2; grid-row-end: 3;}
.grid-container {
  display: grid;
  grid-template-columns: 200px 1fr;
  grid-gap: 10px;
  padding: 10px;
}
.roundrect {border-radius: 30px;}
</style>

<div class="grid-container">
  <div class="item1" style="text-align:center">
  <a href="{{ site.url }}{{ site.baseurl }}/software/iraclis/"><font size="6"><b>Iraclis</b></font></a>
  </div>
  <div class="item2">
  <a href="{{ site.url }}{{ site.baseurl }}/software/iraclis/"> <img class="roundrect" src="{{ site.urlimg }}/iraclis.jpg" width="200" height="200"></a>
  </div>
  <div class="item3">
  <p align="justify">Iraclis is a stand-alone, dedicated Python package, able to extract exoplanetary spectra from the raw scanning-mode spectroscopic images of the Wide Field Camera 3 (WFC3) onboard the Hubble Space Telescope (HST). Unlike the standard HST pipeline, CalWF3, and the spectroscopic package aXe, Iraclis is designed to take into account the special features of the spectroscopic images obtained using the scanning-mode. The major tasks applied are: reduction/calibration, extraction and light-curve fitting. The reduction/calibration process includes the following steps: zero-read subtraction, reference pixels correction, nonlinearity correction, dark current subtraction, gain conversion, sky background subtraction, alignment, wavelength calibration, flat-field correction, and bad pixels/cosmic rays correction. The spectral extraction takes into account the non uniform structure of the spectrum across the WFC3/IR detector. Finally, Iraclis makes use of PyLightcurve (further down) to fit for the transit/eclipse light-curves and produce the exoplanetary spectrum. &nbsp; &nbsp; <a href="{{ site.url }}{{ site.baseurl }}/software/iraclis/"><b> Read More </b></a></p>
  </div>
</div>
<br>

<div class="grid-container">
  <div class="item1" style="text-align:center">
  <a href="{{ site.url }}{{ site.baseurl }}/software/wayne/"><font size="6"><b>Wayne</b></font></a>
  </div>
  <div class="item2">
  <a href="{{ site.url }}{{ site.baseurl }}/software/wayne/"> <img class="roundrect" src="{{ site.urlimg }}/wayne.jpg" width="200" height="200"></a>
  </div>
  <div class="item3">
  <p align="justify">Wayne is a Python package that simulates Hubble Space Telescope (HST) / Wide Field Camera 3 (WFC3) grism spectroscopic frames, including sources of noise and systematics. It can simulate both staring and spatial scan modes, and observations such as the transit and the eclipse of an exoplanet. Unlike many other instrument simulators, the focus of Wayne is on creating frames with realistic systematics in order to test the effectiveness of different data analysis methods in a variety of different scenarios. This approach is critical for method validation and optimizing observing strategies. &nbsp; &nbsp; <a href="{{ site.url }}{{ site.baseurl }}/software/wayne/"><b> Read More </b></a></p>
  </div>
</div>
<br>

<div class="grid-container">
  <div class="item1" style="text-align:center">
  <a href="{{ site.url }}{{ site.baseurl }}/software/pylc/"><font size="6"><b>PyLightcurve</b></font></a>
  </div>
  <div class="item2">
  <a href="{{ site.url }}{{ site.baseurl }}/software/pylc/"> <img class="roundrect" src="{{ site.urlimg }}/pylc.jpg" width="200" height="200"></a>
  </div>
  <div class="item3">
  <p align="justify">PyLightcurve is a Python package for modeling and analysing transit light-curves. It offers a range of useful functions for transit modelling, such as: easy search for parameters of current exoplanets, calculation of limb-darkening coefficients for a range of different models (also custom ones, upon request) and instruments, calculation of exoplanetary orbits, calculation of the transit model, and flexible fitting of transit light-curves simultaneously with instrumental systemtics. By default, these systematics are polynomials up to 2nd order, but can be adjusted to any other kind of systematics and instruments, upon request. &nbsp; &nbsp; <a href="{{ site.url }}{{ site.baseurl }}/software/pylc/"><b> Read More </b></a></p>
  </div>
</div>
<br>

<div class="grid-container">
  <div class="item1" style="text-align:center">
  <a href="{{ site.url }}{{ site.baseurl }}/software/hops/"><font size="6"><b>HOPS</b></font></a>
  </div>
  <div class="item2">
  <a href="{{ site.url }}{{ site.baseurl }}/software/hops/"> <img class="roundrect" src="{{ site.urlimg }}/hops.jpg" width="200" height="200"></a>
  </div>
  <div class="item3">
  <p align="justify">HOPS (HOlomon Photometry Software) is a pipeline to analyse data from small ground-based telescopes. The major tasks applied are: reduction, alignment, photometry and light-curve fitting. It also includes a Graphic User Interface which allows the easy and flexible analysis of observations without any knowledge of the programming language (Python in this case). &nbsp; &nbsp; <a href="{{ site.url }}{{ site.baseurl }}/software/hops/"><b> Read More </b></a></p>
  </div>
</div>
<br>

<div class="grid-container">
  <div class="item1" style="text-align:center">
  <a href="{{ site.url }}{{ site.baseurl }}/software/transitsim/"><font size="6"><b>TransitSim</b></font></a>
  </div>
  <div class="item2">
  <a href="{{ site.url }}{{ site.baseurl }}/software/transitsim/"> <img class="roundrect" src="{{ site.urlimg }}/transitsim.jpg" width="200" height="200"></a>
  </div>
  <div class="item3">
  <p align="justify">Graphic interface for transit visualisation. &nbsp; &nbsp; <a href="{{ site.url }}{{ site.baseurl }}/software/transitsim/"><b> Read More </b></a></p>
  </div>
</div>
<br>

<div class="grid-container">
  <div class="item1" style="text-align:center">
  <a href="{{ site.url }}{{ site.baseurl }}/software/adsilib/"><font size="6"><b>ADSiLib</b></font></a>
  </div>
  <div class="item2">
  <a href="{{ site.url }}{{ site.baseurl }}/software/adsilib/"> <img class="roundrect" src="{{ site.urlimg }}/adsilib.jpg" width="200" height="200"></a>
  </div>
  <div class="item3">
  <p align="justify">ADS Library Organiser. &nbsp; &nbsp; <a href="{{ site.url }}{{ site.baseurl }}/software/adsilib/"><b> Read More </b></a></p>
  </div>
</div>
<br>