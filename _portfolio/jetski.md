---
title: "Design and Fabrication of Custom Jetski for Coastal Surveying"
permalink: /portfolio/jetski
#excerpt: "Boston, MA<br/><img src='/images/jesseJetski.jpg'>"
excerpt: "<a href='/portfolio/jetski'><img src='/images/jesseJetski.jpg'></a>"
collection: portfolio
---

To facility acquiring bathymetric information in shallow water, I designed and built a custom bumper that affixes to the back of a jetski and houses a sonar 
transducer, inertial motion unit (IMU), and GNSS receiver.  The first step was scouring the internet for a lightly used, well maintained jetski in the greater
New England area. This was not an easy task but years of Facebook Marketplace experience served me well and I finally found a suitable option on the cape. 

![Figure](https://tylermccormack-research.github.io/images/newJetskiDay.jpg "Newly acquired jetski")

The next step was using structure from motion (SFM) to create a 3D rendering of the jetski to design the bumper. I took a video of the jetski while walking around it
several times, each time with a slightly different angle. I split the videos into individual frames and uploaded them to Adobe Substance 3D Sampler. After trying various setting configurations, I had a 3D mesh of the jetski. Now using the checkboard I placed on the swim platform of the jetski during the video, I was able to transform it into a 1:1 scale 3D object.

![Figure](https://tylermccormack-research.github.io/images/jetskiHandMeasurements.jpg "Checkerboard and hand measurements for SFM calibration")

With the 3D I designed a bumper in Fusion 360 and 3D printed it at full scale for a test fit. The prototype fit perfectly! 

 <div align="center">
  <img src="https://tylermccormack-research.github.io/images/3dPrintedBumper_b.jpg" alt="3D Printed Jetski Bumper Prototype" width="40%">
  <img src="https://tylermccormack-research.github.io/images/3dPrintedBumper_c.jpg" alt="3D Printed Jetski Bumper Prototype Mounted on Jetski" width="40%">
</div>

Working with the fabrication shop and a local welder, we turned the 3D printed prototype into the final metal assembly. Thanks to the precision work by everyone it also fit like a glove! 

 <div align="center">
  <img src="https://tylermccormack-research.github.io/images/plasticToMetal.jpg" alt="Transforming the 3D printed prototype into the final metal assembly" width="40%">
  <img src="https://tylermccormack-research.github.io/images/preWeld.jpg" alt="Metal bumper pieces before welding" width="40%">
</div>

![Figure](https://tylermccormack-research.github.io/images/metalBumper.jpg "The final product!")

The main advantages of the this bumper design is that it bolts on using the existing mounting points for the swim step and the entire instrument array pole can be easily rotated out of the water to avoid damage while in transit to the survey location. It also provides the opportunity to update design as necessary and add additional instrumentation (such as a side-scan sonar) in the future. 

<div align="center">
  <img src="https://tylermccormack-research.github.io/images/surveyPoleUp.jpg" alt="Instrument pole up in the surveying position" width="40%">
  <img src="https://tylermccormack-research.github.io/images/surveyPoleDown.jpg" alt="Instrument pole down in the transit position" width="40%">
</div>

I also 3D printed platform for the data acquisition computer to sit on in the frunk of the jetski to keep it secure and raised off the ground incase any water got into the waterproof front compartment. 

<div align="center">
  <img src="https://tylermccormack-research.github.io/images/platformB.jpg" alt="Data acquisition computer on 3D printed platform" width="30%">
  <img src="https://tylermccormack-research.github.io/images/platform.jpg" alt="3D printed platform in jetski frunk" width="30%">
  <img src="https://tylermccormack-research.github.io/images/platformC.jpg" alt="Data acquisition computer on 3D printed platform in jetski frunk" width="30%">
</div>

Finally, I designed a fixture to mount the waterproof tablet used to control the data acquisition to the steering column of the jetski. The tablet has a SIM card giving it cellular connection to enable network-RTK corrections.
<div align="center">
  <img src="https://tylermccormack-research.github.io/images/tabletMount.jpg" alt="Waterproof tablet mounted to jetski steering column" width="40%">
  <img src="https://tylermccormack-research.github.io/images/tabletInAction.jpg" alt="Tablet in action" width="40%">
</div>

And voila, ready to survey!
![Figure](https://tylermccormack-research.github.io/images/jesseJetski.jpg "Jesse Beckman doing a survey of Nahant Bay, MA")

Jetskiing is fun but can be a bit chilly in May 🥶
![Figure](https://tylermccormack-research.github.io/images/brr.jpg "Tyler docking after a cold day of testing in the Spring")

Fun fact: 
I used the same structure from motion techniques to make a 3D printed bust for the Civil Engineering Department chair, Jerry Hajjar, when he retired.

<div align="center">
  <img src="https://tylermccormack-research.github.io/images/jerryPlastic.jpg" alt="Waterproof tablet mounted to jetski steering column" width="40%">
  <img src="https://tylermccormack-research.github.io/images/jerryStone.jpg" alt="Tablet in action" width="40%">
</div>


