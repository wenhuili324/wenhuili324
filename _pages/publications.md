---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<!--- reverse ordered list in html, not an 'easy' way to do this in markdown without another package -->
<br>
<ol reversed>

<h2 style='margin-top:0'>2024</h2>

<li>
Y. Nan, A. MacKerell, Balancing Group I Monoatomic Ion-Polar Compound Interactions for Condensed Phase Simulation in the Polarizable Drude Force Field, Journal of Chemical Theory and Computation, 2024, 20, 8, 3242--3257
</li>

<li>
W. Li, Y. Nan, Z. Jin, Dependence of Methane Transport on Pore Informatics in the Amorphous Nanoporous Kerogen Matrix, Langmuir, 2024, 40, 1, 687–695
</li>

<h2 style='margin-top:0'>2023</h2>


<li>
L. Duan, M. Zhang, Y. Nan, Z. Jin, Effects of Interfacial Molecular Structures on Pressure-Driven Brine Flow in Silica Mesopores, Langmuir, 2023, 39, 37, 13019–13027 
</li>

<li>
M. Zhang, Y. Nan, Y. Lu, Q. You, Z. Jin, CO2-responsive surfactant for oil-in-water emulsification and demulsification from molecular perspectives, Fuel, 2023, 331 (2): 125773
</li>



<h2 style='margin-top:0'>2022</h2>
  
<li>
Y. Fujisawa, Y. Nan, A. Asano, Y. Yanagisawa, K. Yano, Y. Itoh, T. Aida, Blending to Make Nonhealable Polymers Healable: Nanophase Separation Observed by CP/MAS 13C NMR Analysis, Angew. Chem. Int. Ed., 2022, e202214444
</li>


<li>
Y. Nan, W. Li, Z. Jin, Molecular Dynamics Studied on Effective Surface-Active Additives: Toward Hard Water-Resistant Chemical Flooding for Enhanced Oil Recovery, Langmuir, 2022, 38 (16): 4802-4811
</li>

<li>
Y. Nan, Z. Jin, Effect of Alcohol Tail Length on Aggregate Behavior of Alcohol and AOT at the Water-scCO2 Interface: MD Simulation Study, Book, Nanostructured Materials for Sustainable Energy: Design, Evaluation, and Applications, Chapter 10, pp 263-288, 2022
</li>

<h2 style='margin-top:0'>2021</h2>
  
<li>
Y. Nan, W. Li, M. Zhang, Z. Jin, Ethanol Blending to Improve Reverse-Micelle Dispersity in Supercritical CO2: A Molecular Dynamics Study, J. Phys. Chem. B, 2021, 125 (33): 9610-9620
</li>

<li>
Y. Nan, W. Li, Z. Jin, Ion Valency and Concentration Effect on the Structural and Thermodynamic Properties of Brine-Oil Interfaces with Anionic Surfactant (SDS), J. Phys. Chem. B, 2021, 125 (33): 9621-9628
</li>

<li>
X. Zhang*, Q. Jin*, Y. Nan*, L. Hou, B. Li, X. Chen, Z. Jin, X. Zhang, J. Huang, and Q. Zhang, Electrolyte Structure of Lithium Polysulfides with Anti‐Reductive Solvent Shells for Practical Lithium-Sulfur Batteries, Angew. Chem. Int. Ed., 2021, 60: 15503-15509 *Co-first Author
</li>

<li>
W. Li, Y. Nan, Q. You, Z. Jin, CO2 solubility in brine in silica nanopores in relation to geological CO2 sequestration in tight formations: Effect of salinity and pH, Chem. Eng. J., 2021, 411: 127626
</li>

<li>
W. Li, M. Zhang, Y. Nan, W. Pang, Z. Jin, Molecular Dynamics Study on CO2 Storage in Water-Filled Kerogen Nanopores in Shale Reservoirs: Effects of Kerogen Maturity and Pore Size, Langmuir., 2021, 37(1): 542–552
</li>


<h2 style='margin-top:0'>2020</h2>

<li>
W. Li, Y. Nan, Z. Zhang, Q. You, Z. Jin, Hydrophilicity/Hydrophobicity Driven CO2 Solubility in Kaolinite Nanopores in Relation to Carbon Sequestration, Chem. Eng. J., 2020, 398: 125449
</li>

<li>
Y. Nan, W. Li, Z. Jin, Roles of alcohol as a cosurfactant at brine-oil interface under a typical reservoir condition, Langmuir, 2020, 36(19): 5198-5207
</li>

<li>
W. Li, Y. Nan, Q. You, Q. Xie, Z. Jin, Effects of salts and silica nanoparticles on oil-brine interfacial properties under hydrocarbon reservoir conditions: A molecular dynamics simulation study, J. Mol. Liq., 2020, 305: 112860
</li>

<li>
X. Hu, Y. Nan, X. Kong, D. Lu, and J. Wu, A hybrid theoretical method for predicting electrokinetic energy conversion in nanochannels, Phys. Chem. Chem. Phys., 2020, 22(16): 9110-9116
</li>

<li>
Y. Nan, W. Li, Z. Jin, Slip length of methane flow under shale reservoir conditions: Effect of pore size and pressure, Fuel, 2020, 259: 116237
</li>


<h2 style='margin-top:0'>2019</h2>

<li>
W. Li, Y. Nan, X. Wen, W. Wang, Z. Jin, Effects of Salinity and N-, S-, and O-Bearing Polar Components on Light Oil–Brine Interfacial Properties from Molecular Perspectives, J. Phys. Chem. C, 2019, 123, 38, 23520-23528
</li>


<h2 style='margin-top:0'>2018</h2>
  
<li>
Y. Yanagisawa, Y. Nan, K. Okuro, T. Aida, Mechanically robust, readily repairable polymers via tailored noncovalent cross-linking. Science, 2018, 359(6371): 72 – 76. 
</li>

<h2 style='margin-top:0'>2017</h2>

<li>
Y. Nan, X. Kong, J. Li, D. Lu, Non-equilibrium Molecular Dynamics Simulation of Water Flow Inside Nano-slit. Journal of Chemical Industry and Engineering, 2017, 68(5): 1786 – 1793.
</li>
</ol>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
