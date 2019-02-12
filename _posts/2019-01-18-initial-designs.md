---
layout: post
title: Initial Designs
date: 2019-01-18 12:00:00 +0800
categories: [log]
---
<style>
  .wrapper {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(45vh, 1fr));
    grid-gap: 20px;
  }
  .item > img {
    width:100%;
  }
</style>

# Diagrams

<div class="wrapper">
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/IMG_6262.JPG" />
  </div>
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/IMG_6263.JPG" />
  </div>
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/IMG_6264.JPG" />
  </div>
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/IMG_6265.JPG" />
  </div>
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/IMG_6266.JPG" />
  </div>
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/IMG_6554.JPG" />
  </div>
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/IMG_6555.JPG" />
  </div>
  <div class="item">
    <img src="/speaalpha18/asset_images/diagrams/blockdiag.png"/>
  </div>
</div>

# The Photos
As seen in the photos above, our team has came out with both the mechanical and electrical design for our submersible ROV. The final electrical connections are shown by the last image, a digital block diagram. The first few images show the various ideas the team was throwing around in implementing the various features. Though slightly different from the final form, the principles and reasoning are more of less the same. A buoy to be on the surface to transmit and receive control and data signals. Originally no battery present on the buoy itself, the decision to place the batter on the buoy came from space issues on the ROV and the difficulty of getting the battery in and out of the electronics compartment itself. A few changes also include the sensors which are not present in the final product due to time constraints, and an additional arduino uno to provide cleaner input/output signals to/from various components.

# Electrical
Originally, our plan was to use a buck converter to step down the voltage of the battery that is being provided. It is because by stepping down the voltage, our team would then be able to power stuff like the Arduino, camera and etc., at a suitable voltage without spoiling those devices. For the motors, it will be connected to a motor shield that is custom design to withstand around 12v of DC supply. This is to ensure that our motors in return will be able to get sufficient voltage to spin at a suitable speed. Last but not least, there is also another shield which is the receiver for our PS2 controller.

# Mechanical
Mechanical-wise, the shape of our submersible ROV is that of an submarine but with added wings on both side of the body. This is to stabilize the boat much better. We also have plan to use epoxy and resin to waterproof our submarine to prevent water from entering as it would cause a hazard if water were to come in contact with our electrical components.

We also have decided to have a buoy that will be attached to the main submersible ROV. The reasons are firstly, the signal are not strong enough to penetrate under water which will not let us be in control when using the wireless PS2 controller to control our boat.