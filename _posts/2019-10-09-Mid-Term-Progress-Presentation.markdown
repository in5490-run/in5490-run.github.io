---
layout:     	slide
title:     		Mid-term progress presentation
author:     	Håkon, Ole og Vegard
tags:           presentation 
subtitle:    	Presentation of problem, possible solution and related work.
mcl_video_id: "Mlp27dQZ7ws?start=9"

theme:		moon # default/beige/blood/moon/night/serif/simple/sky/solarized
trans:		cube # default/cube/page/concave/zoom/linear/fade/none

horizontal:	</section></section><section markdown="1" data-background=""><section markdown="1">
vertical:		</section><section markdown="1">
---
<section markdown="1" data-background=""><section markdown="1">
## {{ page.title }}

<hr>

#### {{ page.author }}

#### {{ "October 14, 2019" | date: "%a - %d %b %Y"}}

{{ page.horizontal }}
<!-- Start Writing Below in Markdown -->

## UAV Localization

* Global vs Local
* Sensors
    * Inertial navigation system(INS)
    * Visual odometry
    * GPS/GNSS
* Monte Carlo Localization(MCL)

{{ page.horizontal }}

## Monte Carlo Localization

{% include youtubePlayer.html id=page.mcl_video_id %}

{{ page.horizontal }}

## Problems

* Robustness:
    * Lighting conditions
    * Environmental changes
* Optimization:
    * Response time
    * Computational power

{{ page.horizontal }}

### First priority: Increasing robustness using ML

* Semantic segmentation
    * Feature extraction 
    * Faster local-localization
    * Invariance to
        * Lighting conditions
        * Environmental change 

{{ page.horizontal }}

### 2nd priority: Optimizing MCL
* Hush-hush / No idea yet

{{ page.horizontal }}

## System

![System diagram](/img/system.png)

{{ page.horizontal }}


![Comparison](/img/comparison.jpg)

{{ page.horizontal }}

## Progress 7%
### <progress value="7" max="100"></progress>

* [x] Obtain data
    * [x] Map Data
    * [ ] Flight videos
* [ ] Create data-set 
* [ ] Test different ML Models
    * [ ] U-NET
    * [ ] Adaptnet
* [ ] Evaluate models
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
