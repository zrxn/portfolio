---
layout: post
title:  "Watchdog Project – CETIAsia 2016"
date:   2016-12-16 20:27:56 +0800
categories: jekyll update
---
Well today, we are attending CETIAsia 2016 challenge. My watchdog project have been selected under the top 10 finalist!

Prize appreciation ceremony with Mr. George Choo (Seito Singapore)

Here is the link to view a video on my project :

![award](/images/award.jpg)

https://www.youtube.com/watch?v=zl2T3LcxGsM

So basically, what is this project about?

I was having Intern at a Small-Medium Enterprise (based in Singapore) which provides various types of commercial solutions from Self – Service kiosk to Digital Signage which make use of Media Box to run the software to display its’ contents and run its’ applications. With over few thousands of its’ products throughout the whole of Singapore, we faced problems from the Media Box it uses like:

Hanging

Digital devices such as media box would tend to hang due to insufficient memory or overheating. A way to solve this issue is to simply restart the Media Box and the company is always sending their technical down to just turn off and on the Media Box, resulting in inefficient manpower management.

Over-Heating

In places like SBS bus interchange where the Digital Signage are displayed in the outdoors, the Media Box mounted on the back of the Digital Signage are exposed to sunlight throughout the day and thus, malfunctions because of the surrounding heat.

Solution?

Therefore, in order to properly govern its’ man-power and make use of them efficiently, our company would like us to create a device to monitor the status of their Digital Signage, namely the SBS Departure and Advertisement banners. We are creating an independent device that could monitor the Android Media box whether if it is hanged, its’ surrounding humidity and temperature and if the monitor is displaying anything.  The project has to be created within a limited budget as we need to implement it in many of the locations.

Market Research:

We have realized that many of the advertising company and signage company either digital or non-digital, requires a group of team that have to be on standby all the time almost every day. From our daily life, we encountered many signage’s with downtimes and requires immediate attention.

We went to learn about what factors do company and people consider when engaging an advertising company. Simple, they needed a fuss-free solution where they could convey their message and awareness across to their consumers, also allowing them to make changes such as promotions and timing anytime. This is especially important when deploying for many locations, technicians would need to consider the factor of traveling time.

With this, we have come out with a cheap and simple solution to be able to do a diagnostic remotely without the technician onsite and also executing a reset on the media box.

 

Importance of having a low-cost solution

As a Small-Medium Enterprise, cost considerations would be a major factor for us in order to keep our customer base. We want to have a solution that does not push the pricing factor onto our consumer, at the same time maintaining or even improve our quality of services.

By reducing downtimes, our technician would have more time trying out new projects and products, resulting in a win-win solution. Also, we could provide consistent production of new products with reduced cost, more contact time with our customer to understand their needs and feedbacks.

————————————————————————–

How we started the project?

The effectiveness of the projects is dependent on the team and how well we manage our time to achieve the goals, with only two persons in the team, we have to make sure that each individual fully understands what this project needs. There are two main parts to this project being the implementation and design. We gave ourselves a time frame of about 6 months, which is a very short time-frame. We have to get used to and learn how the system and program work, adding functionalities and features in a micro-controller with a memory restrictions due to size and cost. Every single byte is crucial in this project because we wanted to optimize the system to be responsive even though it’s the first product. Making it host as a web server at the same time allows us to view the status of the system just by visiting the site, no hassles of using proprietary software or tools, by using a simple web browser we are able to do a diagnostic even when using your phone.

 

Within the third or fourth month, we have managed to solve both software issues on micro-controller and android box. Making the mediabox to be able to reply to the micro-controller constantly, even when the app is not running. This software on the mediabox would also automatically trigger upon boot up, so no manual configuration is needed, because a watchdog system should be seamless.

 

On the remaining two months, we started out with the design. Ease of maintenance was our goal, we believe in “One time design, lifetime maintenance”, we would need it to be simple so when our technicians is there to do a part replacement it would only take a couple of minutes.

Innovativeness

Changes the way of maintenance.

A group of technician going onsite to solve the small technical issues every day, travelling from one end to the other end of Singapore, it is no longer the way it should be. By powering all the digital signage with this microcontroller, we could simply remotely control it to fix the minor issues. It is a different approach to maintenance, as oppose to what we would usually see and think.

Innovative product at a cost.

We want to make it as economical as possible for a specific need, where many of the company would find it worthwhile to implement at their venue. We use sensor and Arduino boards which are relatively easy to find and affordable worldwide. By fabricating our own Printed Circuit Boards, we tailored every ports and devices to maximize its potential. Despite that, we make sure that the parts are cross compatible even when fitted into our circuit boards.

How does it work?

With the advancement in technology, many companies have started to use android media box or even NUCs to help them with their daily needs, from POS to Signage’s. However, all if not most of the micro-controllers have a tendency to hang with no reason, being memory leak or overheating. So, we made it able to communicate between both devices and able to check the status of the system by sending a query command from the Watchdog. As Watchdog is an independent device, it would continue to work even when the media box is hang. After receiving a reply, it would continue to diagnose through the temperature sensor to check it is overheating.

For operating hours of company, staff would have to be responsible for the operational hours of the device. We have included a Real-Time Clock and programmed it to be able to schedule a time on and off in case the staff have forgotten to either power on or off.

Custom Printed Circuit Board built using Altium Designer specifically for this project.

Programming of Arduino Uno and Android MediaBox.

CETIAsia Exhibition of Watchdog Project at Expo with my supervisor.

Presenting my project to judges from overseas.

 

You can contact me via email if you would like to know more about this project!