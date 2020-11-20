---
layout: page
title: "Research"
---
<a name="CV"></a>
## <span style="color:#34bdeb"> Lab Assistant</span>
### <img src="/images/location-pin2.png" width="15">{:style="margin-bottom: 5px;""} &nbsp;&nbsp; Washington D.C., USA
---
<br/>
Under construction. Coming soon...

<a href="/index.html#Back2CV">Back</a>
<br/><br/><br/><br/>

<a name="DART"></a>
## <span style="color:#34bdeb"> Senior Thesis Research - Honor</span>
### <img src="/images/location-pin2.png" width="15">{:style="margin-bottom: 5px;""} &nbsp;&nbsp; College Park, Maryland, USA
---
<br/>
I worked with Professor Douglas Hamilton at the department of Astronomy, University of Maryland. My senior honor thesis research was part of the NASA DART project.
<br/>
### [Double Asteroid Redirection Test (DART) Mission](https://www.nasa.gov/planetarydefense/dart)
<img align="Left" width="400" img src="assets/images/DART2.png" >{:style="float: left;margin-right: 30px;margin-top: 15px;margin-bottom: 10px"}<br/>
Double Asteroid Redirection Test is a planetary defense test and it is the first demonstration to use
kinetic impactor technique.

(Simplified goal: Scientists use rockets to hit and change the orbit of the asteroid so it will not destroy the Earth.) The target asteroids are Didymos and its moon.
<br/><br/>
- Didymos-A (primary body) is **(780 ± 8) meters**
- Didymos-B (moonlet) is about **160-meters** in size
- The distance between the primary body and the moonlet is **1.18km**
- DART will be launched using SpaceX rocket in California in **late July 2021**
- DART is predicted to impact moonlet in **late September 2022**
- Ground-based telescopes will measure the change in momentum imparted to Didymos B

[**Here is a simulated impact movie in action**](https://www.youtube.com/watch?v=8zooPRmgUPI)
<br/><br/>
### My research
In order to calculate how the collision will affect the asteroid's orbit, we have to study how the particles on the asteroid would distribute and spread after the collision event. **Our research aimed at converting the surface data (Left) obtained from telescope observations to an actual 3D shape data consists of 10<sup>9</sup> cubes (Right)**.
From the 3D shape, we could calculate the gravitation field of the asteroid and its moon and then we could study and understand how the particle will spread after the collision.

|<img src="assets/images/DART5.png"> | <img src="assets/images/DART6.png"> |
|:--:||:--:|
| *Raw Data: <br/>Didymos-A surface from telescope observation* | *After algorithm: <br/>Didymos-A 3D shape data consists of cubes* |


My algorithm worked as follows:
1. Create a space with 100 x 100 x 100 cubes
2. Find out the location of the surface in the space
3. Mark space outside as 0 (None), space with borders as 0.5 (Half-filled), and space inside as 1 (Filled)
4. Perform error-checking functions to see
  - if the input/provided surface data is complete and correct
  - if the constructed surface is complete

The image on the bottom-right shows a sketch 2D cross-section of the 3D shape.

- 1 = inside ;  0.5 = border ;  0 = outside

| <img src="assets/images/DART3.png"> | <img src="assets/images/DART4.png"> |
|:--:||:--:|
| *Didymos-A at another angle* |  *2D cross section print of the 3D shape* |

<a href="/index.html#Back2DART">Back</a>
<br/><br/><br/><br/>

<a name="ASIAA"></a>
## <span style="color:#34bdeb"> ASIAA Summer Student Program</span>
### <img src="/images/location-pin2.png" width="15">{:style="margin-bottom: 5px;""} &nbsp;&nbsp; Taipei, Taiwan
---
<br/>
### Trans-Neptunian Object (TNO)
<img src="assets/images/ASIAA3.png" width="350" >{:style="float: left; margin-right: 35px; margin-top: 56px; margin-bottom: 45px"}

**Simplified Definition**: Any "rock" within solar system that is further than planet Neptune is called TNO.

Wikipedia: A trans-Neptunian object (TNO), is any minor planet or dwarf planet in the Solar System that orbits the Sun at a greater average distance than Neptune, which has a semi-major axis of 30.1 astronomical units (AU).

Here are some famous TNOs in the image on the left. Most of them are small, distant, and dim so it is hard for us to see and track them even with telescopes. But scientists believe that by studying the distribution of TNOs, we can discover the evolution of the solar system.
<br/>

### Survey Telescope
Survey telescope is built for ultra-wide area observations. Compared to normal telescope, it can observe many objects at once by scanning a large area of the sky. From the captured images, researcher can determine the orbits of interesting objects. My research project goal is to use simulation to support a proposal to use Subaru Telescope in Hawaii.  
<br/>
### FOSSIL - A Telescope Proposal
<img src="assets/images/ASIAA2.png" width="400" >{:style="float: right ;margin-left: 35px; margin-top: 15px; margin-bottom: 10px"}

“the Formation of the Outer Solar System: an Icy Legacy” **(FOSSIL) is**

- An ASIAA proposed survey to use Subaru telescope in Hawaii (image on the right)
- Study TNOs close to ecliptic plane
- Study different sub groups of TNO

All TNOs discovered will be carefully tracked to reliably classify their orbits.
<br/>Total request is **35 nights over 3 years with an average 5 nights per semester**.
<br/><br/>
**FOSSIL will  …**

- Answer fundamental questions about the formation and evolution of the Solar System
- Leverage Subaru Telescope large field of view (**Very wide image capture**) and sensitivity (**See lots dimmer TNOs**) to survey 176 sq.deg. of nightsky and to mr (Stellar object luminosity magnitude) = 26.1

<p align="center">
  <img src="assets/images/ASIAA4.png">
  Areas of interest in the FOSSIL proposal. My research focus on the KOZAI area
  <br>
</p>
- The graph above is similar to the map of the Earth, where you convert the whole year night sky globe to a 2D rectangular with Right Ascension (Astronomy Longitude) and  Declination (Astronomy Latitude).
- The Sin/Cos curve is the ecliptic plane (the sun's orbit in our (night) sky)
- N = Neptune; &nbsp;&nbsp; S = Saturn; &nbsp;&nbsp; J = Jupiter; &nbsp;&nbsp; U = Uranus

<br>
### My research
We wanted to maximize the actual telescope discovery results in the KOZAI regions because of the actual limited telescope observing time. Our simulation used TNO distribution models and ran test observations to see the potential number of TNO detections. We use python and fortran to deploy 20 observation areas around the KOZAI region as shown in the figure below.

<p align="center">
  <img src="assets/images/ASIAA1.png">
  1 set of 10 observation areas in our simulation
  <br>
</p>
And the simulation results on 2 sets of area are shown below, where observation region 6_6 and 6_5 are resulting more TNO detections:

<p align="center">
  <img src="assets/images/ASIAA5.png">
  2 sets of total 20 observation areas in our simulation
  <br>
</p>

We updated the result in the proposal for Subaru Telescope.

<a href="/index.html#Back2ASIAA">Back</a>
<br/><br/><br/><br/>

## <span style="color:#34bdeb"> Independent Research - Observatory</span>
### <img src="/images/location-pin2.png" width="15">{:style="margin-bottom: 5px;""} &nbsp;&nbsp; College Park, Maryland, USA
---
<br/>
Under construction. Coming soon...
<br/>
