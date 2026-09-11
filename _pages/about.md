---
permalink: /
title: "About Me"
excerpt: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👩🏻‍🔬 About Me
I am a Ph.D. student in the 
<a href="https://cee.illinois.edu/" style="color: #000000; text-decoration: none; font-weight: bold;">Department of Civil and Environmental Engineering (CEE)</a> 
at the University of Illinois Urbana-Champaign, advised by 
<a href="https://cee.illinois.edu/directory/profile/barros" style="color: #000000; text-decoration: none; font-weight: bold;">Prof. Ana P. Barros</a>. 

My research focuses on using **satellite gravimetry (GRACE/GRACE-FO)** and **land surface models** to detect where terrestrial water storage is changing across North America and to attribute those changes to groundwater depletion or climate variability. 
I work at the intersection of <strong>satellite hydrology</strong>, <strong>groundwater</strong>, and <strong>data assimilation</strong> with hybrid physics–ML modeling.  




# 🔍 Research Interests
- Satellite gravimetry (GRACE/GRACE-FO) for detecting and attributing terrestrial water storage change  
- Groundwater depletion and aquifer-scale water budgets from the residual between GRACE and land surface models  
- Data assimilation and hybrid physics–ML approaches for integrating satellite observations into hydrologic models

<span class='anchor' id='-news'></span>
# 🔥 News
- *2026.09*: &nbsp;🎉 Our paper on crop yield estimation in the Canadian Prairies was accepted in **Agricultural and Forest Meteorology**!
- *2025.12*: &nbsp;🎉 Presenting a poster at the **AGU 2025 Fall Meeting**  
  [View abstract](https://agu.confex.com/agu/agu25/meetingapp.cgi/Paper/1899125)
- *2024.01*: &nbsp;🎉 Our paper on assimilating GRACE total water storage into CLM5-BGC was published in **Journal of Hydrology**!  


<span class='anchor' id='-publications'></span>
# 📝 Selected Papers

<!-- Paper 3 -->
<p>
[3] <em><strong> Chi, H.</strong></em>, Guan, K., Lin, Z., Zhang, J., Wang, S., Mezbahuddin, S., Zhou, Q., & Zhao, K. (2026).  
Spatiotemporal yield estimation of four major crops in the Canadian Prairies using remote sensing and environmental data.
<strong><em>Agricultural and Forest Meteorology (Accepted)</em></strong><br>

<details>
  <summary style="color:#555; cursor:pointer; margin-top:0.4em;">
    Click to view summary
  </summary>
  <span style="color:#555; display:block; margin-top:0.6em; line-height:1.55;">
    Developed a CNN–Transformer architecture that characterizes multi-scale environmental and vegetation signals, enabling high-resolution yield prediction and interpretable spatial–temporal feature attribution.
  </span>
</details>
</p>

<!-- Paper 2 -->
<p>
[2]<em><strong> Chi, H.</strong></em>, Seo, H., & Kim, Y. (2024).  
Hydrological trends captured by assimilating GRACE total water storage data into the CLM5-BGC model.  
<strong><em>Journal of Hydrology, 629</em></strong>, 130527.  
<a href="https://doi.org/10.1016/j.jhydrol.2023.130527" style="color:#000000; text-decoration:underline;">
  doi:10.1016/j.jhydrol.2023.130527
</a><br>

<details>
  <summary style="color:#555; cursor:pointer; margin-top:0.4em;">
    Click to view summary
  </summary>
  <span style="color:#555; display:block; margin-top:0.6em; line-height:1.55;">
    Improved CLM5-BGC terrestrial water storage representation via GRACE TWSA assimilation, enhancing hydrologic variable fidelity and quantifying anthropogenic signals in long-term hydrological trends.
  </span>
</details>
</p>

<!-- Paper 1 -->
<p>
[1] Seo, J., <em><strong>Chi, H.</strong></em>, Kim, H. J., & Kim, Y. (2022).  
Hydrological drought risk assessment for climate change adaptation in South Korea.
<strong><em>Journal of Korea Water Resources Association, 55(6)</em></strong>, 421–435.  
<a href="https://doi.org/10.3741/JKWRA.2022.55.6.421" style="color:#000000; text-decoration:underline;">
  doi:10.3741/JKWRA.2022.55.6.421
</a><br>

<details>
  <summary style="color:#555; cursor:pointer; margin-top:0.4em;">
    Click to view summary
  </summary>
  <span style="color:#555; display:block; margin-top:0.6em; line-height:1.55;">
    Assessed future hydrological drought risks under multiple climate scenarios and identified region-specific vulnerabilities to inform national climate adaptation planning.  
    (Written in Korean with English abstract)
  </span>
</details>
</p>


<span class='anchor' id='-field-experiences'></span>
# 🚜 Field Experiences  
<details>
  <summary style="font-size:1.1rem; cursor:pointer; font-weight:600;">
    📌 Soil Moisture Monitoring Campaign (2023-2024) (click to expand)
  </summary>
  <br>

  <table>
    <tr>
      <td style="vertical-align: top; padding-right: 20px; line-height:1.55;">
        <strong>Soil Moisture Monitoring Campaign (2023–2024)</strong><br>
        <em>Hands-on experience integrating in-field sensor networks with satellite remote sensing for agricultural monitoring.</em><br><br>

        • Led large-scale field campaigns across 30 commercial farms in Illinois to deploy and maintain a 58-station soil moisture monitoring network. <br>
        • Installed and operated Acclima TDR-310W sensors with CR300 dataloggers for automated, multi-depth (5–50 cm) soil moisture measurements. <br>
        • Performed sensor calibration and QA/QC, managing long-term time-series data for satellite validation and land surface model evaluation. <br>
        • Coordinated with farmers, technicians, and research teams to maintain continuous data collection.
      </td>

      <td style="vertical-align: top;">
        <img src="images/Fieldwork1.JPG" alt="Soil Sensor Installation" width="250" style="border-radius: 10px;">
      </td>
    </tr>
  </table>
</details>



<span class='anchor' id='-educations'></span>
# 📖 Educations
- *2023.05 – Present*, Ph.D. student, <a href="https://cee.illinois.edu/" style="color: #000000; text-decoration: none;font-weight: bold;">University of Illinois Urbana-Champaign</a>.<br>(Advisor: <a href="https://cee.illinois.edu/directory/profile/barros" style="color: #000000; text-decoration: none;font-weight: bold;">Prof. Ana P. Barros</a>, CEE; 2023–2026 with <a href="http://faculty.nres.illinois.edu/~kaiyuguan/" style="color: #000000; text-decoration: none;font-weight: bold;">Prof. Kaiyu Guan</a>, NRES)
- *2021.03 – 2022.02*, M.S. in Civil and Environmental Engineering, <a href="https://civil.yonsei.ac.kr/civil_en/index.do" style="color: #000000; text-decoration: none;font-weight: bold;">Yonsei University</a>. (Advisor: <a href="https://hecl.yonsei.ac.kr/" style="color: #000000; text-decoration: none;font-weight: bold;">Prof. Yeonjoo Kim</a>)
- *2016.03 – 2021.02*, B.S. in Interdisciplinary Eco Science, <a href="https://www.sungshin.ac.kr/dmse/index" style="color: #000000; text-decoration: none;font-weight: bold;">Sungshin Women's University</a>.

