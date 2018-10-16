# IW532: Hyperlocation Technology: Opportunities and Challenges in an IoT World  

**What** overview of how Real Time Kinematics (RTK) works and presentation of field testing  
**Where** GRB 330A  
**When** Friday, September 28, 2018 11:30 AM  
**Who** Jean McManus  

### problem
* traditional GPS is not accurate enough for use cases like autonomous vehicles - even a meter in error is too much
* error is introduced through atmospheric conditions which can change by location, time of day, weather
  * tropospheric
  * iosspheric (?)

#### DGPS (Differental GPS) 
* +- 1 meter
* 4 satellites minimum
* rover must be 100-200 km from base station

#### RTK (Real Time Kinematic) 
* +- 2 cm
* 5 satellites minimum
* rover must be 10-20 km from base station
* uses alpha phase of the signal from sattellites to figure out error correction

#### base station
* located at a known longitude, lattitude, altitude  
* broadcasts correction info

#### considerations
* if you have 5 base stations which are all sending correction info, you can make a model to figure otu what the error correction is for a point in between them - so now you have a 'virtual' station  
* number of IoT devices is on the rise so any solution will need to scale
* idea: cell phone towers could broadcast correction for their location (as opposed to new GPS base stations)

