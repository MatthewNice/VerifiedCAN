

## Accelerator: message id=705

Plots for the accelerator show when the gas pedal is pressed, and by how much.

### Plotting Accelerator Proportion:
---
This plot was created by using message id 705. 
 
![Accelerator](gas_pedal.png)
---

### Plotting Accelerator Released:
---
This plot uses the same message id, and shows when the pedal was totally released (foot off the pedal).

![Released Gas](gas_released.png)
---

### See both combined:
---
Here they are overlaid to see how they go together, and then with the longitudinal acceleration added showing how the accelerator data lines up as it should with acceleration. Notice how large spikes in acceleration coincide with the large bumps in accelerator being depressed. Notice also how when there are large decelerations the pedal is released (presumably the brake pedal is also being pressed too). There are lots of evironmental factors that affect acceleration and accelerator use such as traffic density, speed limit, and road grade that aren't shown here, but this is still a convincing set of plots.

![both signals](gas_overlay.png)
![pedal with accelx](gas_vs_accelx.png)
---
