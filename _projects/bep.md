---
layout: page
title: event-based dataset
description: Collecting an event-based dataset for a quadrupedal robot for my thesis.
img: assets/img/bep/quadrupedal.jpg
importance: 1
category: uni
related_publications: false
---


For my bachelor thesis for Mechanical Engineering we where tasked to produce an event-based dataset for a quadrupedal robot. Lots of fancy words, but it basically means attach a new fancy camera to a robot dog. This event-based part comes from the camera, an event-based camera. 

This camera has a non-traditional sensor, only capturing changes in light instead of a frame. This means events come in asynchronously, providing an almost instant perception of the world. More benefits include a much smaller datastream while keeping relevant information and the camera never over or underexposing, which could happen to robots when flying / walking into buildings or back outside.


<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bep/event-based.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bep/quadrupedal.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bep/robotcams.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>


It can be seen in the plot that event-based data is streamed continuously on a nanosecond scale.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bep/timeline_plot.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>


The final report is shown below. Alternatively you can download it [here](/assets/pdf/BEP_Report.pdf) and view the code [here](https://github.com/SuperJappie08/BEP-Unitree-Event)

<object data="/assets/pdf/BEP_Report.pdf" width="100%" height="1000" type='application/pdf'></object>
