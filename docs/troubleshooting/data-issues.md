---
layout: default
title: Data issues
nav_order: 5
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/data-issues
---

# Data issues
{: .no_toc }

1. TOC
{:toc}

---

## No deliveries
If you are sure, that you should receive the delivery and the setup of settings in the application is correct, and you are still not receiving any orders, check the other options below or contact [the support](mailto:support@orderlord.com).

## Not receiving assigned deliveries
It could happen, that the application isn't receiving the notifications about newly assigned deliveries. This is caused by the push message logic, which is renewing the token for the device approximately every 1-2 hours. Once this state will occur, the application is trying to send this new token to the server and fix it with that receiving the notifications. But it could happen, that during sending this information to the server, the Android device is not connected to the network. In that case, the application is displaying the warning message "The application isn't synced with the server!". In that case, you need to click on that message, and syncing the token with the server will be initialized.

## "Your GPS position is older than 5 minutes" warning message
Once the courier successfully logs into the application, the warning message on the top could be displayed. This message means, that even if the GPS of the device is running, it could take time, once the GPS is stable and is receiving the near location. If even after a minute-two the application isn't able to find the position of the device, you could speed up the process by opening any of the navigation application, like **"Google Maps"**, **"Waze"**, **"MapFactor"**, etc.. In these applications, the device should be able to do so known "fix GPS", which will reset the searching mechanism, clear the GPS buffered data cache of founded satellites, etc.. Once these applications will fix the GPS, return to the Driver application and the warning message should disappear.

## Past events in the Timeline section
Once the user needs to check the history of the events, that he performed during working with the application, he could use the {% include icon.html name="timeline" %} [**Timeline**]({{site.baseurl}}{% link docs/timeline-section/timeline-section.md %}) section. <span class="text-red-200">But be aware, the number of events logged for the timeline is limited, depending on the device. Once the application was uninstalled, or the cache of the application was deleted (through device Settings), **the timeline data will be deleted**. The application is also storing the only limited value of Timeline data, approximately for the last 7 days.</span>

## Insufficient permission for the restaurant
<span class="text-red-200">If the user is not receiving the orders, it could be because of that the user hasn't permission to work the restaurant. Ask the manager to add the correct restaurants, which he could work with.</span>