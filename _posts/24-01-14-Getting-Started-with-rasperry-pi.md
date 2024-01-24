---
layout: post
title:  "Setting up Rasperry Pi Device"
categories: [ Rasperry Pi ]
image: assets/images/setting_up_rasperry_pi/rasperry_pi_image.jpg
---

I recently bought a Raspberry Pi to delve into Data Engineering tasks related to IoT. In this context, envision IoT as a sensor device capable of measuring various parameters and transmit the data. As an illustration, position an IoT device either indoors or outdoors to gauge temperature and subsequently transmit the gathered data.

I ordered the Raspberry Pi through [The Pi Hut][pi-hut], 8 GB. 

Additionally, the power cable and a micro SD card are essential. A micro USB to HDMI cable is required to link the device to a monitor, and either wired or wireless mouse and keyboards are necessary, given the device's four USB slots. These constitute the necessary hardware.

Moving in to the software, the device doesn't come with a pre-installed OS, like the Windows OS in the laptop. 

The micro SD card functions as the Pi device's hard disk. The Raspberry Pi OS serves as the operating system for the device and must be installed on the SD card before inserting it into the device slot.


## Installing the Rasperry Pi OS in the SD card. 

<li>Insert the memory card in the laptop (Windows/MAC/Linux)</li>
<li>Install the Raspberry Pi Imager from the link: </li>

   [https://www.raspberrypi.com/software][link-link] 

<li>Once installed, run the Imager, the below image will pop up. </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/0.png)

<li>Chose the device, OS and the storage  </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/1.png)

<li> An option to customise will pop up in the next window. Click EDIT SETTINGS </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/2.png)

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/3.png)

<li> Setup the username and password and configure the WIFI, so that you don't need to configure this later in the device </li>

<li> Save and press yes next </li>

<li> This will start writing the OS in the memory card  </li>

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/4.png)

Once installed, it is ready to go. 

Connect the power cable and monitor, insert the memory card and monitor. After a few minutes, the home screen will appear.

![walking]({{ site.baseurl }}/assets/images/setting_up_rasperry_pi/5.png)
<!-- 
Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk]. -->

[pi-hut]: https://thepihut.com/products/raspberry-pi-5
[link-link]: https://www.raspberrypi.com/software/


<!-- 
[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/ -->