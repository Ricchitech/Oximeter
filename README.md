# Oximeter Project
Max30100 pulse Oximeter

#### you will learn how to use the Max30100 Pulse Oximeter with Arduino and display the Heart Rate and Blood Oxygen on a 16×2 LCD. The Heart rate or Pulse rate or Heartbeat is measured in BPM which is also known as the beats per minute while the Blood Oxygen Concentration is measured in percentage.

##### So, basically, the max30100 sensor is a Pulse Oximetry and heart rate monitor which is used to check the health of a person with any condition that affects blood oxygen levels, such as:

1. Heart Attack
2. Heart failure
3. Lungs Cancer
4. Asthma etc.

###### in which I displayed the Blood Oxygen and Heart Rate values on the I2C supported 16×2 LCD and also sent the Blood Oxygen and BPM values to the Android cell phone application.

## What is Pulse Oximetry?
##### Pulse Oximetry is a test used to measure the oxygen level i.e. oxygen saturation of the blood. It is an easy, painless measure of how well oxygen is being sent to parts of your body furthest from your heart, such as the arms and legs.

##### Max30100 Pulse Oximeter is an amazing sensor, still it has some disadvantages it may generate incorrect readings if the finger is not properly placed. The ambient light falling on the sensor can affect the final reading. While using the Max30100 Oximeter, make sure your finger is not moving because it can result in an incorrect reading. One more thing that you really need to take care of while using the Max30100 Sensor is that, never press the sensor too hard as this affects the blood flow and as a result you will get incorrect readings. Try to place your finger softly and make sure your finger does not move, this way you can get the most accurate reading.

##### This is my first getting started tutorial on the Max30100 pulse Oximeter which covers the extreme basics including

1. Max30100 Pulse Oximeter technical specification
2. Max30100 sensor Pinout
3. Interfacing Max30100 Pulse Oximeter Sensor with Arduino
4. Programming and finally
5. Testing

## How an Oximeter works?
##### Oxygen Saturation

##### Pulse Oximeter measure oxygen saturation. Before we learn the principles of how pulse Oximeter work, we need to have an understanding of what oxygen saturation is. Oxygen enters the lungs and then is passed on into blood. The blood carries the oxygen to the various organs in our body. The main way oxygen is carried in our blood is by means of hemoglobin. The hemoglobin without oxygen we will call de oxygenated hemoglobin (deoxy Hb). The hemoglobin with oxygen, we will call oxygenated hemoglobin (oxy Hb).

![image](https://user-images.githubusercontent.com/35210955/111873037-6665d380-89b4-11eb-8e46-ae708352b3e7.png)

##### Oxygen saturation simply refers to the percentage of the available hemoglobin that carries oxygen. Take the situations below. There are 16 hemoglobin units and none of the 16 have oxygen. The oxygen saturation is therefore 0 %.

![image](https://user-images.githubusercontent.com/35210955/111873054-809fb180-89b4-11eb-8e2a-2b3a046c7d51.png)

##### And if it carries the 75% oxygen

![image](https://user-images.githubusercontent.com/35210955/111873062-9319eb00-89b4-11eb-8bcb-f03798b65886.png)

##### And if all the blood cells carries the oxygen then of course it is going to be 100%.

![image](https://user-images.githubusercontent.com/35210955/111873100-ae84f600-89b4-11eb-876c-32ab92efd754.png)

##### The Oximeters comes in different shapes and sizes, but the overall working principle of the pulse Oximeters is exactly the same. Some are of the clip type like the one you can see in the picture above, while some works on the reflection technique, as the one I am using works on the reflection. So when the light passes or reflects we can measure the Oxygen concentration.


## About the Max30100 Pulse Oximeter Sensor:

![1](https://user-images.githubusercontent.com/35210955/111873429-41726000-89b6-11eb-93a0-abdd9a673f27.png)

##### General Description:
###### The MAX30100 is an integrated pulse Oximetry and heartrate monitor sensor solution. It combines two LEDs, a photodetector, optimized optics, and low-noise analog signal processing to detect pulse Oximetry and heart-rate signals.

##### SpO2 Subsystem
###### The SpO2 subsystem in the MAX30100 is composed of ambient light cancellation (ALC), 16-bit sigma delta ADC, and proprietary discrete time filter.

###### The SpO2  ADC is a continuous time oversampling sigma delta converter with up to 16-bit resolution. The ADC out-put data rate can be programmed from 50Hz to 1kHz. The MAX30100 includes a proprietary discrete time filter to reject 50Hz/60Hz interference and low-frequency residual ambient noise.

![image](https://user-images.githubusercontent.com/35210955/111873491-7bdbfd00-89b6-11eb-831a-ad62cf6b54ae.png)

###### As per the system block diagram which is available in the datasheet, it clearly shows that there should be small distance between the sensor and finger.

##### Max30100 Pulse Oximeter Sensor Technical Specification:
###### The MAX30100 operates from 1.8V and 3.3V power supplies.

### Applications
1. Wearable Devices
2. Fitness Assistant Devices
3. Medical Monitoring Devices
4. Max30100 Pulse Oximeter Sensor Pinout:

![1](https://user-images.githubusercontent.com/35210955/111873531-b0e84f80-89b6-11eb-83d3-5acac6969850.png)

###### As you can see clearly the GY-Max30100 Pulse Oximeter has a total of 5 male headers which are clearly labeled as VIN, GND, SCL, SDA, and INT. This is an i2c supported sensor and communicates with the Arduino board through i2c communication bus.

### Interfacing Max30100 Pulse Oximeter Sensor with Arduino Circuit Diagram:

![1](https://user-images.githubusercontent.com/35210955/111873573-e4c37500-89b6-11eb-8fb7-cc62896d3f15.png)

### https://www.electroniclinic.com/wp-content/uploads/2020/02/MAX30100.zip" Download: Max30100 pulse Oximeter Arduino Library


### Interfacing Max30100 Pulse Oximeter Sensor and 16×2 LCD with Arduino Circuit Diagram:

![1](https://user-images.githubusercontent.com/35210955/111873627-44218500-89b7-11eb-9cd7-29e07b91cbe5.png)





















