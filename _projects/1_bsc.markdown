---
layout: page
title: BSc Project
description: Making a robot inspired by the human eye
img: /assets/img/robot_cad.jpg
---

I worked on this project from ground up, to make the concept of human eye robot a reality. First I designed a body that is able to host webcam and small servos. It is also able to provide pathes for nylon coated wires. 

<div class="img_row">
    <img class="col three left" src="{{ site.baseurl }}/assets/img/robot_cad.jpg" alt="" title="CAD model of the eye robot"/>
</div>
<div class="col three caption">
    CAD model of the eye robot in Autodesk Inventor 2016 environment.
</div>
Then I made a <a href="https://github.com/hamidosooli/XL_320Toolbox" target="blank">MATLAB toolbox</a> for the controller board to be able to communicate with PC (and laptop) through MATLAB environment. 


<div class="img_row">
    <img class="col two left" src="{{ site.baseurl }}/assets/img/ext.jpg" alt="" title="example image"/>
    <img class="col one left" src="{{ site.baseurl }}/assets/img/IMG_0460_copy3.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
    Eye robot connected to a laptop that runs MATLAB.
</div>

The first controller which was implemented on this robot was a simple Proportional Integral Derivative (PID) controller. This controller used MATLAB face tracker to help eyes track human face in front of them. A video of these experiments is available <a href="https://www.youtube.com/watch?v=1mQl93-Jzi8" target="blank">here</a>.

