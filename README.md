[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/kzkUPShx)

# a14g-final-submission

    * Team Number: 18
    * Team Name: DataRacers
    * Team Members: Saibaba Nagrund, Deepak Shankar Ravisankar
    * Github Repository URL: https://github.com/ese5160/a14g-final-submission-t18-dataracers
    * Description of test hardware: Custom DataRacers PCBA

## 1. Video Presentation

 <https://youtu.be/YIpAmdMHwzU>

## 2. Project Summary

### Device Description

#### What problem is your device solving? How do you use the Internet so augment your device functionality?

The device we've developed aims to address the challenge of data logging in amateur racing leagues. We observed that while data is crucial for optimizing racecar setups and driver performance, existing solutions are often prohibitively expensive, complex to install and operate, and designed for professional teams with substantial budgets.

Our device offers a cost-effective and user-friendly alternative tailored specifically for amateur racing clubs and drivers. It provides essential data logging functionalities without unnecessary complexities, making it accessible to a broader range of users operating on minimal budgets.

To augment our device's functionality, we leverage the internet in several ways:

1. Data Analysis and Visualization: We utilize the Nodered platform and tools to analyze and visualize the data collected by our device. This enables users to gain insights into their performance, identify areas for improvement, and make data-driven decisions for optimizing their racecar setups and driving techniques.

2. Remote Monitoring and Support: Through internet connectivity, we offer remote monitoring and support services. This allows us to troubleshoot issues, provide software updates, and offer guidance to users regardless of their geographical location, enhancing the overall user experience and ensuring continuous functionality of our device.

Overall, by integrating internet-enabled functionalities into our device, we enhance its usability, accessibility, and value proposition, empowering amateur racing enthusiasts to harness the power of data to improve their performance on the track.

### Inspiration

#### What inspired you to do the project?

Our inspiration for this project stemmed from our passion for Formula One racing. As avid fans of the sport, we were deeply fascinated by the high-stakes, high-speed world of professional racing and the cutting-edge technology employed by Formula One teams to gain a competitive edge.

However, as we delved deeper into the realm of motorsports, we realized that the vast majority of racing enthusiasts operate in amateur leagues with significantly smaller budgets compared to their professional counterparts. Despite their passion and dedication, these amateur racers often face numerous challenges, including limited access to advanced technology and data analytics tools.

This realization sparked the idea of developing a solution that could democratize access to data logging technology for amateur racing leagues and drivers. Rather than trying to reinvent the wheel in the professional racing sphere, we saw an opportunity to make a meaningful impact by addressing the specific needs and challenges of the amateur racing community.

By focusing on data logging—a critical aspect of optimizing racecar performance and driver skill—we aimed to create a solution that would empower amateur racers to enhance their competitiveness and enjoyment of the sport. Our goal was to leverage our expertise and passion for motorsports to develop a practical, affordable, and user-friendly device that could level the playing field and enable amateur racers to unlock their full potential on the  track.

### Device Functionality

### Challenges

Our challenges included the integration of the servo motor with the SAMW25 microcontroller, particularly due to the active spoiler system. The servo's activation depended on the motor's RPM, which required considerable effort to configure properly. Additionally, the 3D printing process for our model proved to be time-consuming. Originally, we intended for the 3D model to feature maneuverability, envisioning printed components like the wheelbase and accel. However, after printing, we encountered static components, unable to move as intended. This issue, coupled with the need for more power to propel the car, led us to power only one part of the wheel.

### Prototype Learnings

Building and testing our prototype, which involved custom PCB design, 3D modeling, and sensor-microcontroller integration using Atmel Studio, taught us valuable lessons. We learned the importance of proper power circuitry and signal routing, especially for SPI communication, to ensure the PCB's functionality. Using Altium Designer improved our skills in handling complex circuit designs. Although initially unfamiliar, learning CAD modeling with SolidWorks was a rewarding experience. Understanding real-time operating systems (RTOS) allowed us to integrate multitasking, improving the device's responsiveness and reliability. Employing Git for version control enhanced our collaborative coding efforts and project workflow. Rigorous testing and streamlined project management were crucial for harmonizing hardware and software integration.

### Next Steps

### Takeaways from ESE5160

### Project Links

#### Node-Red Dashboard - <http://172.191.242.245:1880/ui/>

#### A12G Code Repository - <https://github.com/ese5160/a12g-firmware-drivers-t18-dataracers>

#### Altium 365 - <https://upenn-eselabs.365.altium.com/designs/B30BCA82-12BB-4789-9F4A-3266D740E17A>

## 3. Hardware & Software Requirements

## 4. Project Photos & Screenshots

### 3D Printed Race-Car

![alt text](IMG_3412.jpg)

### Test Setup

![alt text](IMG_4328.jpg)

### Custom PCBA Top

![alt text](IMG_4317.jpg)

### Custom PCBA Bottom

![alt text](IMG_4316.jpg)

### Custom PCBA Thermals

![alt text](Thermal1.jpeg)

![alt text](Thermal2.jpeg)

### Altium Board Design 2D

![alt text](<Altium Board Design 2D.jpg>)

### Altium Board Design 3D

![alt text](<Altium Board Design 3D.jpg>)

### Node-Red Dashboard Frontend

![alt text](Dashboard_DataRacers.png)

### Node-Red Dashboard Backend

![alt text](<Node-Red Dashboard Backend.jpg>)

### System Block Diagram
