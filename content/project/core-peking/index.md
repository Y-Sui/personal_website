---
title: Optimization simulation of reflow welding
summary: Optimization simulation of reflow welding based on prediction of regional center temperature field.
tags:
- Machine Learning
date: "2020-03-27T00:00:00Z"

weight: 50

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
#url_code: ""
url_pdf: "uploads/2021-8-10-16750-CS56209.pdf"
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
slides: ""
---

**Abstract**:
Before reflow soldering of integrated electronic products, the numerical simulation of temperature control curve of reflow furnace is crucial for selecting proper parameters and improving the overall efficiency of reflow soldering process and product quality. According to the heat conduction law and the specific heat capacity formula, the first-order ordinary differential equation of the central tem-perature curve of the welding area with respect to the temperature distribution function in the furnace on the conveyor belt displacement is obtained. For the gap with small temperature difference, the sigmoid function is used to obtain a smooth interval temperature transition curve; For the gap with large temperature difference, the linear combination of exponential function and primary function is used to approach the actual concave function, so as to obtain the complete temperature distribution function in the furnace. The welding parameters are obtained by solving the ordinary differential equation, and a set of optimal process parameters consistent with the process boundary are obtained by calculating the mean square error between the predicted temperature field and the real temperature distribution. At the same time, according to the above established prediction method based on the regional center temperature field, a set of reflow optimization strategies are designed for the actual needs of specific industrial production scenarios: speed interval prediction strategy under given temperature parameters, minimum parameter interval prediction strategy of solder pastes melting reflow area, and the most symmetrical parameter interval prediction of solder paste melting reflow area. The simulation results show that the temperature field prediction results obtained by this method are highly consistent with the actual sensor data, and have strong correlation. This method can help to select appropriate process parameters, optimize the production process, reduce equipment commissioning practice and optimize the solder joint quality of production products.