## Steering Angle: message id=37

[![Steering Angle Video](http://img.youtube.com/vi/RlswOAV-BDg/0.jpg)](http://www.youtube.com/watch?v=RlswOAV-BDg "Steering Angle")<br/>
Video shows reading steering angle live.<br/>
</br>
The following plots were generated using the [strym](https://github.com/jmscslgroup/strym) package that is used to decode, visualize, and analyse CAN bus messages.<br/> 
The goal here is to verify that the message with id 37 provides the steering angle.<br/> Message 37 has two signals: steeing angle and steeting rate.<br/> The csv file contains raw CAN bus messages, and it was recorded under the following conditions:
+ The vehicle is stationary. 
+ Start recording CAN data
+ Rotate the steering wheel to an extreme end, hold for a second and then rotate to the other extreme end.
+ Stop CAN recording.
+ Verify CAN data recording saved.


### Speering angle and steering rate:
--- 
The steeing angle and steeting rate singals are plotted side by side. The y-axis is deg/sec.
 
![Steering Angle](steering_angle.png)
---

### Integration of steering rate:
---
Using the integration function implemented in [strym](https://github.com/jmscslgroup/strym) package, we plotted the steeting rate after integration.

![Steering Angle](integ_rate.png)
---

### Speering angle and the integrated steering rate:
---
By plotting the speering angle and the integrated steering rate on the same figure, the two graphs seem to be identical. This makes us confident that steeing angle singnal is reporting correct values.

![Steering Angle](steering_integRate.png)
---
