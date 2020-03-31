---
layout: default
title: GPS issues
nav_order: 2
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/gps-issues
---

# GPS issues
{: .no_toc }

1. TOC
{:toc}

---

## "High accuracy required!" warning
Once the GPS module isn't enabled or the mode of GPS localization is low, <span class="text-red-200">the dialog with warning message **High accuracy required!** is displayed.</span> This issue could be occurred because of one from multiple things. The courier needs to be sure, that the GPS has the correct setup. Click on the <span class="text-red-200">CHANGE SETTINGS</span> button.

{% include img_smartphone.html name="troubleshooting_gps_issues_1.png" %}

- the Location screen will be displayed. The courier needs to change the **LOCATION MODE** to **HIGH ACCURACY** (some vendors will a moment after this change displays the dialog, which the courier needs to approve). 

{% include img_smartphone.html name="troubleshooting_gps_issues_2.png" %}

{% include img_smartphone.html name="troubleshooting_gps_issues_3.png" %}

- the courier needs also on this screen to scroll down to the list of **LOCATION SERVICES** <span class="text-red-200">(some vendors and models don't need to contain this part of the Location screen).</span> He needs to click on every option from there services and after opening the detail of specific service, the courier needs to **ENABLE** that specific service. This specific restriction is because some models aren't considered, that they are using **HIGH ACCURACY** mode, only after enabling all of these services.

{% include img_smartphone.html name="troubleshooting_gps_issues_4.png" %}

{% include img_smartphone.html name="troubleshooting_gps_issues_5.png" %}

{% include img_smartphone.html name="troubleshooting_gps_issues_6.png" %}

## "Your GPS position is older than 5 minutes" warning message
Once the courier successfully logs into the application, the warning message on the top could be displayed. This message means, that even if the GPS of the device is running, it could take time, once the GPS is stable and is receiving the near location. If even after a minute-two the application isn't able to find the position of the device, you could speed up the process by opening any of the navigation application, like **"Google Maps"**, **"Waze"**, **"MapFactor"**, etc.. In these applications, the device should be able to do so known "fix GPS", which will reset the searching mechanism, clear the GPS buffered data cache of founded satellites, etc.. Once these applications will fix the GPS, return to the Driver application and the warning message should disappear.

## GPS tracking permission also on the background
The Driver application needs for the purposes of tracking the driver permission for the location. From the Android version 9.0 and above, the mechanism of finding the GPS position of the device changed. The device will during accepting this permission asks if the application should have access for the location permission **"only while using the app"** or **"all the time"**. Even that we will appreciate asking only for permission while using the app, the driver could during delivering the orders put the application to the background and for instance, starts the navigation application **"Google Maps"**. And our system needs to track the driver the whole time, while he is traveling to the customer, so that is the reason for **"all the time"** option.