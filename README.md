
# DFFS

## Analyzing the Doppler Free Saturation Spectroscopy of Rubidium using Python

---

**About the project**

![](/img/python_icon.png)

This repository contains Python code for analyzing data from a real-world quantum mechanics lab experiment. The experiment involved using laser pulses to excite Rubidium atoms in a vapor cell, aiming to uncover key features of the atomic structure.

---

<br/>

# Background
<br/>  
Rubidium(Rb) is part of the alkali metals and has atomic number 37. Alkali elements are characterized by a closed shell configuration of the inner electrons and a single valence electron which gives them a ”hydrogen-like” structure and properties.


<div style='text-align: center;' class='img_row'>
    <img class='col two' src='{{ site.baseurl }}/img/Rb5.jpeg' alt='' title='example image'/>
</div>
<div class='col two caption'>
    Image credit <a href='https://commons.wikimedia.org/wiki/User:Dnn87'>Dnn87</a>. This file is licensed under the <a href='https://en.wikipedia.org/wiki/en:Creative_Commons'>Creative Commons</a> <a href='https://creativecommons.org/licenses/by/3.0/deed.en'>Attribution 3.0 Unported</a> license.
</div>
<br/>       
The quantization of angular momentum has important implications for the energy levels of the hydrogen atom. For example, the energy levels of the hydrogen atom are split into multiple sublevels due to the different possible values of the electron's orbital angular momentum and spin angular momentum. This splitting of the energy levels is known as the fine structure of the hydrogen atom.

To detect the fine and hyperfine splitting of energy levels, we can use a spectrometer to measure the wavelength or frequency of electromagnetic radiation produced during transitions between energy levels.

<div style='text-align: center;' class='img_row'>
    <img class='col two' src='{{ site.baseurl }}/img/Rb.jpeg' alt='' title='example image'/>
</div>
<div class='col two caption'>
    Actual image from the experiment showing the laser beam passing through the rubidium cell. 
</div>
<br/>       
When an atom or molecule absorbs a photon of energy, it can be excited to a higher energy level. When the atom or molecule decays back to a lower energy level, it emits a photon of energy. The wavelength or frequency of the emitted photon is characteristic to the energy difference between the two energy levels.

However, due to the fine and hyperfine splitting of the energy levels, the emitted photon can have multiple wavelengths.

Using the spectrometer we can measure the intensity of the photons at each wavelength. The resulting spectrum will have different peaks corresponding to each wavelength. First, the fine structure can be analyzed by locating and measuring the distance between peaks. Next, by applying a counter-propagating laser beam to reduce the absorption rate of the initial probe, the hyperfine structure will be revealed by the appearance of dips corresponding to transitions from the ground state to the hyperfine levels of the excited state.

<div style='text-align: center;' class='img_row'>
    <img class='col two' src='{{ site.baseurl }}/img/fine_peaks.png' alt='' title='example image'/>
</div>
<div class='col two caption'>
    The Gaussian fit to the Doppler broadened signal showing the frequency separation between the Rubidium-87 F=1 and F=2 levels. 
</div>


<br/><br/><br/>



