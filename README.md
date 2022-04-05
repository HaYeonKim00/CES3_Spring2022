# CES3_Spring2022

## For Arduino File

#### Multicore to use parallelism 
In order to rotate two motors at the same time xTaskCreatePinnedToCore() is used. We set ```int taskCore``` to 1 and this is where we want our second motor to run on. In coreTask(), we are running our first motor. 

#### Running servo motor
```runMotor()``` is running our servo motor.

#### Running stepper motor
```moveSteps()``` is running our stepper motor.

## For wifi API

#### Link for the kinetic-sculpture-webapi
Our entire class used this [link](https://github.com/mbennett12/kinetic-sculpture-webapi) for the start button. By adding the example code provided in the link, when we clicked the button in the 134.122.113.13/our-uni, we could start our device. And by clicking the button generated through 134.122.113.13/server, all of the buttons that were generated before was clicked at the same time. The IP address was made for this class by our professor. 

#### connecting wifi
For the wifi set up code part, after assigning ssid_Router and password_Router, we can connect it by using ```WIFI.begin()```. Make sure that you are using the same wifi for the IP address as well. 

## Video
[CES3_spring2022](https://youtu.be/axDH8re7FYI)
