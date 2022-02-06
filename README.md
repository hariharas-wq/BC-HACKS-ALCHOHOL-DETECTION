# BC-HACKS-ALCHOHOL-DETECTION
## Inspiration
During a recent incident, 3 of my friends died in a car accident due to the influence of alcohol. It was after this incident that I was fueled by the desire to implement something which could save people's life. Saving the lives of not only the ones driving under the influence of alcohol but also people who can be harmed due to this. As we know that we can’t stop people from drinking alcohol but we can avoid having such accidents due to drowsiness. This lead us to the idea of building this Arduino based IOT implementation to save lives. 

## What it does
This project was designed for the safety of people sitting inside the car as well as the people outside on the streets. This project works on an Arduino based system. The MQ3 sensor used detects whether the person driving the car is under the influence of alcohol or not. The concentration of alcohol gas in the air is detected by the sensor which outputs its reading as an analog voltage. The concentration sensing range of 0.04 mg/L to 4 mg/L has been used (the legal limit of breath alcohol concentration, or BrAC, in most US states is 0.08 grams per 210 litres or 0.38 mg/L). If the concentration is above the threshold value provided, the DC motor stops running, thus bringing the car to a halt. After the car is at a halt, it will not start again unless the concentration of alcohol detected comes below the threshold value. This does not allow the driver to drive under the influence of alcohol which in return might save lives. 

## How we built it
We built this project by integrating an alcohol sensor with an Arduino board in it. We have used Arduino processor ATmega328p as it is able to handle more functions than conventional microcontrollers. The alcohol sensor we have used in this project is MQ3 which helps detect the alcohol content in 
the human breath. Since the sensor has a fine sensitivity range of around 2 meters, it can suit any vehicle and can easily be hidden in the vehicle. It can also operate at temperatures from -10 to 50°C and consumes less than 150 mA at 5 V. It is also very compact to fit in a complete set-up in the form of a product in an automobile. We have also used a 16x2 LCD display to show alert messages whether the person is under influence or not. We have also attached a DC motor to show that the vehicle can be controlled using the Arduino system.

## Architectute Diagram

![block](https://user-images.githubusercontent.com/63738424/152671961-f431d326-7f3a-410c-865c-e7e2db90aed7.png)

![block1](https://user-images.githubusercontent.com/63738424/152672000-7f16820e-0e76-4f55-b70b-4cfb7dec3cfc.png)


## Circuit Diagram
![block2](https://user-images.githubusercontent.com/63738424/152672060-6c72f2f2-9e56-46e7-9e3f-5e41fd340e86.PNG)


## Model Implementation Diagrams 

![WhatsApp Image 2021-11-27 at 9 33 19 PM (1)](https://user-images.githubusercontent.com/63738424/152672226-7ea51875-6d53-4bf3-acd2-21fe95d7769a.jpeg)
![WhatsApp Image 2021-11-27 at 9 28 39 PM (1)](https://user-images.githubusercontent.com/63738424/152672229-639c1f1e-6cf9-45b0-b3bc-96a4e602de87.jpeg)
![WhatsApp Image 2021-11-27 at 9 21 15 PM (1)](https://user-images.githubusercontent.com/63738424/152672230-d8e406dc-4d60-48bc-9806-8da401ef0950.jpeg)
![WhatsApp Image 2021-11-27 at 6 07 43 PM (1)](https://user-images.githubusercontent.com/63738424/152672232-dd3b1d73-9a88-44f7-811f-f81f6f6eddd8.jpeg)

## Challenges we ran into
1. The most important challenge we faced was to coordinate and build a hardware project staying in different cities. 
2. Finishing the whole project in 1 day.
3. Connecting Arduino with all components.
4. Implementing hardware connections with the power source and the DC motor.
5. Putting together all the various components involved to make a single product.
6. Dumping the Arduino code into the connections.

## Accomplishments that we're proud of
1. Building the whole model within the given timeline. 
2. Design the hardware circuits to build an alcohol seeing device. 
3. Learning how to build hardware projects with equal contribution even after staying in different cities.

## What we learned
We learned to improve our strategies on how to work on a hardware project while living in different cities. This being our first hardware project, we learnt about new IoT implementations which can be applied for the betterment of humans. We have also learned a lot about how Arduino, motors and sensors work. 


## What's next for Alcohol Detection With Vehicle Controlling using Arduino
We can implement GSM technology within the alcohol detector which would inform the relatives or friends if the alcohol levels in the vehicles rise to high values and if the vehicle has come to a halt due to it.
We can also implement a GPS module within our device. This would help us track the location of the vehicle in case of any emergency.
We are planning to add modifications to prevent driving cars under the influence of other drugs.
