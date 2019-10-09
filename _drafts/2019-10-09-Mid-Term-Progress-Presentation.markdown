---
layout:     	slide
title:     		Mid-term progress presentation
author:     	Håkon, Ole og Vegard
tags:           presentation 
subtitle:    	Presentation of problem, possible solution and related work.
mcl_video_id: "PE3V-9dEUS4?t=8"

theme:		moon # default/beige/blood/moon/night/serif/simple/sky/solarized
trans:		cube # default/cube/page/concave/zoom/linear/fade/none

horizontal:	</section></section><section markdown="1" data-background=""><section markdown="1">
vertical:		</section><section markdown="1">
---
<section markdown="1" data-background=""><section markdown="1">
## {{ page.title }}

<hr>

#### {{ page.author }}

#### {{ 'now' | | date: "%I:%M  - %a - %b %d %Y"}}

{{ page.horizontal }}
<!-- Start Writing Below in Markdown -->

## UAV Localization

* Global vs Local
* Sensors
    * INS
    * Video odometry
    * GPS/GNSS
* Monte Carlo Localization(MCL)

{{ page.horizontal }}

## Monte Carlo Localization

{% include youtubePlayer.html id=page.youtubeId %}

{{ page.horizontal }}

## Problems

* Lighting conditions
* Seasonal changes
* Response time
* Computational power

{{ page.horizontal }}

## Increasing robustness using ML

* Segmentation
    * Feature extraction 
    * Decreased work-space
    * Invariance to
        * Lighting conditions
        * Seasonal change 

{{ page.horizontal }}

## Optimizing MCL
* Hush-hush / No idea yet

{{ page.horizontal }}

## Progress 7%
### <progress value="7" max="100"></progress>

* [x] Obtain data
* [ ] Create data-set 
    * [ ] Resolution fix 
    * [ ] Labeling
* [ ] Test different ML Models
    * [ ] U-NET
    * [ ] Adaptnet
* [ ] Train model
* [ ] Test model 
    * [ ] Lighting changes
    * [ ] Seasonal changes
* [ ] Conduct experiment with video
* [ ] (Optional) Conduct experiment RT on drone
* [ ] Write scientific paper and get **world famous**

{{ page.horizontal }}

## Related work

* Vegard: [Deep CNN-Based Framework For Enhanced Aerial Imagery Registration with Applications to UAV Geolocalization](https://github.com/in5490-run/documentation_and_research/blob/master/Papers/Nassar_A_Deep_CNN-Based_CVPR_2018_paper.pdf)
* Ole Edvin: [Vision-based Robot Localization Across Seasons and in Remote Locations, Anirudh Viswanathan, Bernardo R. Pires, and Daniel Huber](https://github.com/in5490-run/documentation_and_research/blob/master/Papers/viswanathan2016.pdf)
* Håkon: [AdapNet: Adaptive Semantic Segmentation in Adverse Environmental Conditions](https://github.com/in5490-run/documentation_and_research/blob/master/Papers/AdapNet%20Adaptive%20Semantic%20Segmentation%20in%20Adverse%20Environmental%20Conditions.pdf)

<!-- End Here -->
{{ page.horizontal }}

# [Print]({{ site.url }}{{ site.baseurl }}{{ page.url }}/?print-pdf#)

# [Back]({{ site.url }}{{ site.baseurl }})

</section></section>
