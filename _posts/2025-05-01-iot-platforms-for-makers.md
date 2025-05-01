---
title: "IoT Platforms for Makers"
date: 2025-05-01T15:48:35-04:00
categories:
  - tools
tags:
  - iot
---

I’ve been looking at several Internet of Things (IoT) cloud platforms to support a new series of connected projects. The ideal platform would have a no-subscription (free) option as well as an affordable paid tier that offers expanded resources when a project requires more. My intended audience of students, makers, scientists and artists will want to get started quickly, with low complexity and an easy path to early success.

Every IoT platform provider arranges pricing differently, which makes it tough to compare them all. Some limit the number of devices, others the number of uploads or storage time. Many providers don’t offer a free tier beyond 30 days, which I’ve found isn’t nearly enough time for first-time users. Some won’t even reveal the details of their pricing structure until you sign up.

Here’s a brief overview I put together for myself. I decided to omit the big cloud systems because they aren’t really designed for individual users and can be maddeningly complex. AWS, Azure, Google, IBM, Oracle, Siemens, Salesforce, Bosch and similar are amazing for industrial IoT systems. They have power and scalability, but I don’t feel they are appropriate for first-timers, so that’s why they are not considered in this review.

| Priority apples | Second priority | Third priority |
|-------|--------|---------|
| ambrosia | gala | red delicious |
| pink lady | jazz | macintosh |
| honeycrisp | granny smith | fuji |

| Name | URL | Free Devices |  Free Uploads/mo |  Free Storage | Basic Plan Cost/mo | Basic Plan Devices |  Basic Plan Uploads/mo | Basic Plan Storage | Basic Plan Name | Notes |
|-----------|---------------------------------------------------------------------|------------|--------------------------|-------------|------------------|------------------| ----------------------------------|------------------|---------------|------------------------------------|
| ThingSpeak | [https://thingspeak.mathworks.com](https://thingspeak.mathworks.com/) | 4 channels   |                   250,000  |  unlimited    | $8                 | 10 channels        |                          2,750,000 | unlimited          | Home            | Free plan has 15-second upload limit |
| Adafruit IO | [https://io.adafruit.com/](https://io.adafruit.com/)                  | 2            |                1,314,000   |  30 days      | $10                | unlimited          |                          2,628,000 | 60 days            | Adafruit IO+    | More uploads and storage available   |
| ThingsBoard | [https://thingsboard.io](https://thingsboard.io/)                     | \-           |  -                         |  -            | $10                | 30                 |                        10,000,000  | 60 days            | Maker           |                                      |
| Blynk       | [https://blynk.io](https://blynk.io/)                                 | 10           |                     30,000 |  1 week       | $99                | 50                 |  unlimited                         | 6 months           | Pro             |                                      |
| Datacake    | [https://datacake.co](https://datacake.co/)                           | 5            |                     15,000 |  1 week       | $150               | 50                 |                                    | 30 days            | Light           | Or pay as you go $2 euros/device     |
| TagoIO      | [https://tago.io](https://tago.io/)                                   | 5            |                1,000,000   |  30 days      | $49                | 100                |                          1,000,000 | 9 years            | Starter         |                                      |
*Packages and prices change all the time, so be sure to confirm with the provider!*

For my projects, I’m leaning toward Adafruit IO because it’s a nice mix of free and low-cost paid options, in a very maker-friendly setup. But I’m also impressed with each of the others for different reasons. Datacake and TagoIO provide wonderful dashboards. ThingsBoard’s paid-tier account offers the best value on uploads while Blynk doesn’t appear to limit uploads at all, providing a great value though at a much higher price. Pick the combination that works best for you!