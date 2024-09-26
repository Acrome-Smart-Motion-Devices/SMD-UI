# SMD UI - The Smart User Interface of Acrome SMD

SMD UI makes it easier to work with SMD products. The users can:

- Monitor, configure and update the firmware of the SMD
- PID Auto-tune the DC motors, taking off the burden of calculating PID values
- Control the DC motors in 4 different operation modes: PWM, Position, Velocity and Current(Torque) modes
- Monitor the plots of the DC motor movements in 3 different operation modes
- Test and interact with all 10 types of SMD Add-on Modules


## Changelog

### Version 0.7 Beta
It is the initial version of the SMD UI that is created in a downloadable form. It has general capabilities of SMD Python Library. It has bugs that are being fixed.


### Version 0.8 Beta
SMD Python Library has updated, thus, the SMD UI's software is updated inside, bringing a new features and fixes many unlisted bugs.

- Reflectance Sensor Module (QTR) values now can be monitored in analog values, these are ranging between [0, 255].
- Acrome's social links and documentation have added to the top bar, into the "Help" and "Community" sections.


### Version 0.9 Beta
In this version, the biggest feature added is the **Trapezoidal** motor control mode. Also now the plots of all motor control modes are available to do pan & zoom, save the plot image, export values etc. that comes with the Matplotlib library.

Also there are minor improvements and bug fixes.

- The SMD UI update check feature is added, it automatically checks if there is a newer version of SMD UI. The user can check from the About section on the top, by clicking the "Check Updates" button.
- IMU values are no longer integer, they are float.
- The data transfer rate of the add-on modules is increased so that the data from the input sensors are printed faster.
- The SMD firmware update feature is now fully operating, it checks for the newer firmware when the button is clicked. If there is not, it will inform the user with a pop-up.

**NOTE:** If you update the firmware of the SMD, you need to restart the SMD UI and SMD itself by power off or factory reset.