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

If the driver isn't receiving even after that deliveries, he could try to check that by [manual update.]({{site.baseurl}}{% link docs/getting-started/update-the-data.md %}) If you aren't able to receive deliveries even after that, please, contact [the support.](mailto:support@orderlord.com)

## Wrong address of the order
If the driver will realize, that the order has the wrong marker on the map depending on it's GPS position, this could be caused by wrong geocoding of the customer address or by wrong integration data. In any of these two cases, he should contact [the support](mailto:support@orderlord.com) or [report the problem]({{site.baseurl}}{% link docs/troubleshooting/report-your-problem.md %}) through Driver application, which is much faster (try to mention the specific order, where is the issue with GPS location of the customer).

## Can't cancel the assigned delivery
Once the newly assigned delivery will be received in the Driver application, the screen, where the driver could/should accept the delivery will be displayed. Some accounts have disabled the option for canceling these assigned deliveries. <span class="text-red-200">In such a case, you need to ask the administrator of the account (_you need to ask for access_).</span> 

## Past events in the Timeline section
Once the user needs to check the history of the events, that he performed during working with the application, he could use the {% include icon.html name="timeline" %} [**Timeline**]({{site.baseurl}}{% link docs/timeline-section/timeline-section.md %}) section. <span class="text-red-200">But be aware, the number of events logged for the timeline is limited, depending on the device. Once the application was uninstalled, or the cache of the application was deleted (through device Settings), **the timeline data will be deleted**. The application is also storing the only limited value of Timeline data, approximately for the last 7 days.</span>

## Insufficient permission for the restaurant
<span class="text-red-200">If the user is not receiving the orders, it could be because of that the user hasn't permission to work the restaurant. Ask the manager to add the correct restaurants, which he could work with.</span>