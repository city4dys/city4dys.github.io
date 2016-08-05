---
layout: post
title:  "Target devices"
date:   2016-08-05 00:00:00
author: Massimiliano Bernabé
categories: development
tags:	device android ios
cover:  "/assets/instacode.jpg"
---

We have to choose between to develop a native mobile application or a web application mobile ready.

|--------|------------|---------|
| Aspect | Native App | Web App |
|--------|------------|---------|
| **General idea** | It is developed with a particular device in mind and is installed | It is internet-based and accessed. Does not work without internet access.  |
| **User Interface** | user-centric: it is very simple to build an application similar to others making the user comfortable | application-centric: android, ios, and windows users does not share a common style, the application will have a different style |
| **Development Process** | Each mobile platform has its language for development, and we have to choose one among them. There are accellerators but we do not have the money to buy a professional one. |  Development will be in HTML, CSS  and Javascript which is good for us. |
| **Accessibility** | Totally compatible with the device, download updates when the application changes | The application uptates itself since is basically a web site. Compatibility is an issue to target different browsers.  |
| **Efficiency** | Faster and more efficent, it is specific for the hardware | Slower, uses scripts though the device's browser.  |
|--------|------------|---------|

## Our choice

We consider the user (which is dyslexic) the highest priority, and the overall performance of the application the second. Our previous experience "OpenStreetMap for the dyslexic" was a web application and suffer a lot in therms of performances.

We explicitly decided that compatibility through different browsers is something we do not want to face, and so the choice can be only one: develop a native application.


## Next step

Now we have to choose which device target first.

|-------------------|--------------|--------|--------------|
| Device            | Market share | Trend  |         Note |
|-------------------|-------------:|:------:|--------------|
| **Android**       |        80.7% | +      | We have a bunch of testing devices | 
| **Blackberry**    |         0.2% | -      | We do not have a testing device |
| **WindowsPhone**  |         1.1% | -      | Our testing device is dead |
| **iOS**           |        17.7% | -      | We do not have a testing device |
| **Others**        |         0.2% | -      |              |
|-------------------|--------------|--------|--------------|

Source: [Gartner 02/2016](http://www.gartner.com/newsroom/id/3215217)

So our choice is to target for android first, and to decide later if to target for iOS too depending on feedback received.

Happy coding!
