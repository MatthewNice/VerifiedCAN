## Longitudinal Speed: message id=180

The following plots were generated using the [strym](https://github.com/jmscslgroup/strym) package that is used to decode, visualize, and analyse CAN bus messages.<br/> The goal here is to verify that the message with id 180 provides the vehicle's speed information.<br/> In order to do that, we plotted the speed of each wheel using message id 170 and the speed from Driving Support Unit (DSU) which gives longitudinal motion using message id 353. These two plots verify that message 180 is indeed reporting speed information. Units are in kph, which was checked by conversion to mph and nominally fitting the velocities of the drive.

### Plotting Speed:
---
This plot was created by using message id 180 which has the speed signal. 
 
![Speed](SpeedId180.png)
---

### Plotting Speed for each wheel:
---
This plot was created by using message id 170 which has the speed signal for each wheel.

![Speed](WheelsSpeed.png)
---

### Plotting Speed from Driving Support Unit (DSU):
---
This plot was created by using message id 353 which has signal for the longitudinal motion.

![Speed](DSU_SPEED.png)
---
