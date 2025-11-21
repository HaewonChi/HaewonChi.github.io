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

## 👩🏻‍🔬 Short Bio
I am a Ph.D. student in the 
<a href="https://nres.illinois.edu/" style="color: #000000; text-decoration: none; font-weight: bold;">Department of Natural Resources and Environmental Sciences (NRES)</a> 
at the University of Illinois Urbana-Champaign, advised by 
<a href="http://faculty.nres.illinois.edu/~kaiyuguan/" style="color: #000000; text-decoration: none; font-weight: bold;">Prof. Kaiyu Guan</a>. 

My research focuses on using **satellite remote sensing** and **machine learning** to monitor crop stresses, predict yield, and detect early signals of crop diseases. 
I work at the intersection of **hyperspectral sensing**, **environmental drivers**, and **AI-driven** agricultural modeling.  
Here is my <a href="assets/HaewonChi_CV4.pdf" style="color: #000000; text-decoration:none;font-weight: bold;">CV</a>.


## 🔍 Research Interests
- Satellite-based crop disease detection and early warning systems  
- Large-scale crop yield estimation integrating ML and environmental drivers  
- Hyperspectral and multispectral fusion for agricultural monitoring  
- Deep learning models for spatiotemporal crop prediction

<span class='anchor' id='-news'></span>
# 🔥 News
- *2025.12*: &nbsp;🎉 Presenting a poster at the **AGU 2025 Fall Meeting**  
  [View abstract](https://agu.confex.com/agu/agu25/meetingapp.cgi/Paper/1899125)
- *2024.01*: &nbsp;🎉 Paper published in **Journal of Hydrology** (GRACE–CLM5 data assimilation)  
- *2023.05*: &nbsp;🎉 Started my Ph.D. program at **UIUC**! 

<span class='anchor' id='-publications'></span>
# 📝 Selected Papers

<p>[3] <strong>Chi, H.</strong>, Guan, K., Lin, Z., Zhang, J., Wang, S., Mezbahuddin, S., Zhou, Q., Zhao, K. (2025) 
"Spatiotemporal Yield Estimation of Four Major Crops in Canadian Prairies using Remote Sensing and Environmental Data". 
<strong><em>Submitted to Agricultural and Forest Meteorology.</em></strong><br>
<span style="color:#555;">- Developed a CNN-Transformer framework that accurately captures spatiotemporal yield variability and quantifies crop- and stage-specific contributions of vegetation and climate signals.</span>
</p>

<p>[2] <strong>Chi, H.</strong>, Seo, H., Kim, Y. (2024) 
"Hydrological trends captured by assimilating GRACE total water storage data into the CLM5-BGC model". 
<strong><em>Journal of Hydrology, 629</em></strong>, 130527.
<a href="https://doi.org/10.1016/j.jhydrol.2023.130527" style="color:#000000; text-decoration:underline;">
doi: 10.1016/j.jhydrol.2023.130527
</a><br>
<span style="color:#555;">
- Improved CLM5-BGC water storage estimates through GRACE TWSA data assimilation, enhancing hydrological variable accuracy and quantifying anthropogenic-driven hydrological trends.
</span>
</p>

<p>[1] Seo, J., <strong>Chi, H.</strong>, Kim, H. J., Kim, Y. (2022) 
"Hydrological drought risk assessment for climate change adaptation in South Korea". 
<strong><em>Journal of Korea Water Resources Association, 55(6)</em></strong>, 421–435.
<a href="https://doi.org/10.3741/JKWRA.2022.55.6.421" style="color:#000000; text-decoration:underline;">
doi: 10.3741/JKWRA.2022.55.6.421
</a><br>
<span style="color:#555;">
- Assessed future hydrological drought risks under climate-change scenarios and identified regional vulnerability across South Korea. 
  (Written in Korean with English abstract)
</span>
</p>


<span class='anchor' id='-field-experiences'></span>
# 🚜 Field Experiences 
*Hands-on experience integrating in-field sensor networks with satellite remote sensing for agricultural monitoring.*

<table>
  <tr>
    <td style="vertical-align: top; padding-right: 20px;">
      <strong>Soil Moisture Monitoring Campaign (2023–2024)</strong><br>
      - Led large-scale field campaigns across 30 commercial farms in Illinois to deploy and maintain a 58-station soil moisture monitoring network. <br>
      - Installed and operated Acclima TDR-310W sensors with CR300 dataloggers for automated, multi-depth (5–50 cm) soil moisture measurements. <br>
      - Conducted sensor calibration, QA/QC, and managed long-term time-series data for satellite validation and land surface model evaluation. <br>
      - Coordinated with farmers, technicians, and research teams to maintain continuous data collection.
    </td>
    <td style="vertical-align: top;">
      <img src="images/Fieldwork1.JPG" alt="Soil Sensor Installation" width="250" style="border-radius: 10px;">
    </td>
  </tr>
</table>

<span class='anchor' id='-educations'></span>
# 📖 Educations
- *2023.05 – Present*, Ph.D. student in Natural Resources and Environmental Science, <a href="https://nres.illinois.edu/" style="color: #000000; text-decoration: none;font-weight: bold;">UIUC</a>.(Advisor: <a href="http://faculty.nres.illinois.edu/~kaiyuguan/" style="color: #000000; text-decoration: none;font-weight: bold;">Prof. Kaiyu Guan</a>)
- *2021.03 – 2022.02*, M.S. in Civil and Environmental Engineering, <a href="https://civil.yonsei.ac.kr/civil_en/index.do" style="color: #000000; text-decoration: none;font-weight: bold;">Yonsei University</a>. (Advisor: <a href="https://hecl.yonsei.ac.kr/" style="color: #000000; text-decoration: none;font-weight: bold;">Prof. Yeonjoo Kim</a>)
- *2016.03 – 2021.02*, B.S. in Interdisciplinary Eco Science, <a href="https://www.sungshin.ac.kr/dmse/index" style="color: #000000; text-decoration: none;font-weight: bold;">Sungshin Women's University</a>.

<span class='anchor' id='-work-experience'></span>
# 💻 Work Experience
- *2023.03 – 2023.05*, Post Masters Researcher at 
  <a href="https://civil.yonsei.ac.kr/civil_en/index.do" style="color: #000000; text-decoration: none;font-weight: bold;">Yonsei University</a>, 
  HECL Lab (Hydrology and EcoClimate Lab), Seoul, Korea. <br>
  (Advisor: <a href="https://hecl.yonsei.ac.kr/" style="color: #000000; text-decoration: none;font-weight: bold;">Prof. Yeonjoo Kim</a>)
- *2022.09 – 2022.12*, Teaching Assistant at <a href="https://www.sungshin.ac.kr/dmse/index" style="color: #000000; text-decoration: none;font-weight: bold;">Sungshin Women's University</a>. Seoul, Korea.