---
layout: page
title: drone firmware
description: Developed an embedded systems application
img: assets/img/esl/esl_drone.jpeg
importance: 2
category: uni
related_publications: false
---

For the course Embedded Systems Lab we had to develop the firmware for a drone, communicating with a client (a PC with a Joystick) and using the joystick input to control the drones yaw, roll, pitch and height. This project had to be done in Rust as latency and lag are a big issue with drones.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/esl/esl_drone.jpeg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/esl/gui_esl.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/esl/raw_mode.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>


The final report is shown below. Alternatively you can download it [here](/assets/pdf/ESL_Report.pdf) and view the code [here](https://github.com/diebolo/esl_drone_controller)

<object data="/assets/pdf/ESL_Report.pdf" width="100%" height="1000" type='application/pdf'></object>
