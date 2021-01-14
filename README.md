#ROS Robotics By Example
This is the code repository for [ROS Robotics By Example](https://www.packtpub.com/hardware-and-creative/ros-robotics-example?utm_source=github&utm_medium=repository&utm_campaign=9781782175193), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.
##Instructions and Navigations
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

XYZ

The code will look like the following:
```
<?xml version='1.0'?>
<robot name="dd_robot">
<!-- Base Link -->
<link name="base_link">
<visual>
<origin xyz="0 0 0" rpy="0 0 0" />
<geometry>
<box size="0.5 0.5 0.25"/>
</geometry>
</visual>
</link>
</robot>
```

The format of this book is intended for you to follow along and perform the 
instructions as the information is provided. You will need a computer with Ubuntu 
14.04 (Trusty Tahr) installed. Other Ubuntu versions and Linux distributions 
may work as well as Mac OS X, Android, and Windows but documentation for 
these versions will need to reference the ROS wiki (http://wiki.ros.org/
Distributions).
The version of ROS that this book was written around is Indigo Igloo, which is the 
current release recommended for stability. Its end of life is targeted for April 2019. 
Other versions of ROS may be used but are untested.
All the software used in this book is open source and freely available for download 
and use. Instructions to download the software are found in the chapter where the 
software is introduced. In Chapter 1, Getting Started with ROS, instructions are given 
to download and set up the ROS software environment.
Our preferred method to download software is the use of Debian packages. Where 
no Debian packages exist, we refer to downloading the software from repositories 
such as GitHub.
Gazebo simulation performs intensive graphics processing and the use of a dedicated 
graphics card is advised but not required.
Peripheral devices such as 3D sensors, Xbox, or PS3 controllers, Arduino or 
Raspberry Pi controller boards, and Android mobile devices are optional equipment.

##Related Products
* [Learning JavaScript Robotics](https://www.packtpub.com/hardware-and-creative/learning-javascript-robotics?utm_source=github&utm_medium=repository&utm_campaign=9781785883347)

* [Learning Robotics Using Python](https://www.packtpub.com/application-development/learning-robotics-using-python?utm_source=github&utm_medium=repository&utm_campaign=9781783287536)

* [Raspberry Pi Cookbook for Python Programmers](https://www.packtpub.com/hardware-and-creative/raspberry-pi-cookbook-python-programmers?utm_source=github&utm_medium=repository&utm_campaign=9781849696623)
###Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
