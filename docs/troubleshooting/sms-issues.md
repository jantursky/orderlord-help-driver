---
layout: default
title: SMS issues
nav_order: 8
has_children: false
has_toc: false
parent: Troubleshooting
permalink: /troubleshooting/sms-issues
---

# SMS issues
{: .no_toc }

1. TOC
{:toc}

---

## Sending SMS to the customer is forcing to send through native SMS application
Because the application is not considered as an **"SMS application"**, the Driver application can't send the SMS directly. It is the restriction of the Android hierarchy, and we aren't able to provide the one-click solution. That is the reason, why right after clicking on ["Notify the customer with SMS/e-mail"]({{site.baseurl}}{% link docs/getting-started/notify-the-customer-with-sms-email.md %}), the official SMS application of the Android device is opened and the driver needs to do one additional click for sending the SMS.